Kviz sa pitanjima vezao za DSG.Dokri zaposleni na IORS-U mogu da preuzmu fajl sa ovog linka.
Fajl treba pokrenuti samo na računarima veće rezolucije.
                      Uputstvo za upotrebu
Ukoliko doktorima treba izmena sadržaja fajla mogu ga otvoriti u nekom od text editora (notepad,notepad++)
na mestu 
-------------------data = [
            {
                question: 'Koji je status dg ekvivalentan OUH-u u DSG-u?',
                options: ['Glavna završna', 'Radna', 'Prateća završna', 'Nijedna od navedenih'],
                correctAnswer: ['Glavna završna']
            },
            {
                question: 'Koji je dokument obavezan pri otpustu pacijenta?',
                options: ['Dekurzus', 'Otpusna lista', 'Izveštaj', 'Matični list'],
                correctAnswer: ['Otpusna lista']
            },
            {
                question: 'Šta sve može da se fakturiše kao prvi pregled',
                options: ['Prvi dolazak pac. u godini-ambulanta', 'Prvi dolazak pac. kod drugog spec.', 'Prvi kontakt u godini-hospitalizacija', 'Nova dijagnoza'],
                correctAnswer: ['Prvi dolazak pac. u godini-ambulanta','Prvi kontakt u godini-hospitalizacija','Nova dijagnoza']
            },
            {
                question: 'Da li hospitalizacija u okviru DB mora da traje 24h',
                options: ['Otpust se vrši u istom kalendarskom danu','Može da traje 24h bez obzira na kalenarski dan'],
                correctAnswer: ['Otpust se vrši u istom kalendarskom danu']
            },
            {
                question: 'Koja se dijagnoza bira kao glavna završna u stacionaru',
                options: ['C-DG', 'Z-DG', 'Komorbiditeti', 'Hronične dijagnoze'],
                correctAnswer: ['C-DG']
            },
            {
                question: 'Do kada se može retroaktivno raditi otpust pacijenta',
                options: ['U roku od 24h', 'Do kraja meseca', 'Do puštanja fakture'],
                correctAnswer: ['Do puštanja fakture']
            },
            


        ];
        -------------------------------------------
se može dodati nov sadržaj
nov sadržaj se dodadje tako sto se u viticastim zagradama dodaju 3 parametra question(text pitanja),options(ponuđeni odgovori),correctAnswer(tačan odgovor (može ih biti više))
primer 
{
                question: 'Pitanje 1',
                options: ['odg1', 'odg2', 'odg3'],
                correctAnswer: ['odg1']
},
options i correctAnswer moraju biti u uglastim zagradama i text mora biti izmedju apostrofa
Važna napomena sadržaj u viticastim zagradama predstavlja jednu celu sekciju, može se dodati na bilo koje mesto unutar ~data~ , samo treba voditi računa da se ispotuje notacija iz primera gore
