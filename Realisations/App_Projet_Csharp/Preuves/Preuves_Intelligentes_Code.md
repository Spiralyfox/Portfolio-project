# Preuves Intelligentes - Application C# (Gestion Appareils)

## 1. La persistance des données via Fichier Texte (Logique Métier)
Dans ce projet, j'ai créé une classe Appareil qui gère elle-même son enregistrement dans le fichier de sauvegarde Appareils.txt.
J'ai utilisé la syntaxe using (StreamWriter...) pour garantir la fermeture et la libération correcte du fichier après l'écriture.

`csharp
// Extrait de Appareil.cs : Sauvegarde des données
public void Save()
{
    // Utilisation d'un chemin relatif vers la pseudo Base de Données
    using (StreamWriter bd = new StreamWriter(""..\..\..\Appareils.txt"", true))
    {
        bd.WriteLine(Id + ""|"" + Name + ""|"" + ItemName + ""|"" + Piece); 
    }
}
`

## 2. Interaction avec l'Interface Graphique (Logique Événementielle)
Dans le code de l'interface Form1.cs, les actions de l'utilisateur (comme le clic sur le bouton de sauvegarde) déclenchent l'instanciation de l'objet et son enregistrement.

`csharp
// Extrait de Form1.cs : Clic sur le bouton de sauvegarde
private void buttonsave_Click(object sender, EventArgs e)
{
    // Génération d'un id aléatoire à 6 chiffres
    Random rnd = new Random();
    int id = rnd.Next(100000, 999999);

    // Création de l'instance temporaire depuis les saisies utilisateur (TextBox & ComboBox)
    Appareil appareil = new Appareil(textBoxName.Text, comboBoxAddName.Text, comboBoxAddPiece.Text, id);

    // Appel de la méthode métier pour enregistrer en base (.txt)
    appareil.Save();

    // Actualisation de l'interface
    UpdateList();
}
`

Ces extraits démontrent ma capacité à séparer la logique métier (Classe Appareil) de la logique événementielle (Form1), un principe fondamental en développement logiciel.
