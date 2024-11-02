def verifier_moyenne(notes):
  
    moyenne = sum(notes) / len(notes)
    if moyenne >= 10:
       return "Réussi"
    else:
        return "Échoué"

notes_etudiant = [12, 15, 9, 13, 10]
resultat = verifier_moyenne(notes_etudiant)
print("Résultat :", resultat)
