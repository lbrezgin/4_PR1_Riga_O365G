# 4_PR1_Riga_O365G

### Papildu prasības programmatūrai 

Spēles sākumā spēles programmatūra gadījuma ceļā saģenerē 5 skaitļus diapazonā no 20000 līdz 30000, bet tādus, kas sākotnēji dalās ar 3, 2 un 4. Cilvēks-spēlētājs izvēlas, ar kuru no saģenerētajiem skaitļiem viņš vēlas sākt spēli. 

### Spēles apraksts 
Spēles sākumā ir dots cilvēka-spēlētāja izvēlētais skaitlis. Abiem spēlētājiem ir 0 punktu. Spēlētāji izdara gājienus pēc kārtas, katrā gājienā dalot pašreizējā brīdī esošu skaitli ar 2,3 vai 4. Skaitli ir iespējams sadalīt tikai tajā gadījumā, ja rezultātā veidojas vesels skaitlis. Ja dalīšanas rezultātā veidojas pāra skaitlis, tad no pretinieka punktiem tiek atņemts 1 punkts, ja nepāra skaitlis, tad paša spēlētāja punkti tiek palielināti par 1 punktu. Spēle beidzas, kā tikko ir iegūts skaitlis, kas ir mazāks vai vienāds ar 10. Ja spēlētāju punktu skaits ir vienāds, tad rezultāts ir neizšķirts. Pretējā gadījumā uzvar spēlētājs, kam ir vairāk punktu. 

### Git Workflow
```bash
git clone repository_name
cd 4_PR1_Riga_O365G
git checkout -b your-branch-name
```

* _Work on your changes, then:_

```bash
git status      # check changed files
git add .       # add all files
git push origin your-branch-name
```

* Then create a pull request from your branch to `main`, but don't merge!
* Nice Work!!! 🎉🥳
