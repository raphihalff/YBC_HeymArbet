Raphael Halff, Steiner Student 2014, raphi.halff@gmail.com
Flash Card Project:
A html project to display images and test the appropriate articles. 

Contents:
        ReadMe.txt (this)
        flashcards.html
        ./images/

To create new flashcards:

-Modify the current copy of flashcards.html or create a new one.
-At the end of the file are JavaScript arrays that look like this: 
 
            var ids = ["1","2","3"];

            var questions = [{yid: "?ווער איז דער מענטש",trans:"Ver iz der mentsh?", eng: "Who is this man?"},
            {yid: "?וואס איז דאס",trans: "Vos iz dos?", eng: "What is this?"},
            {yid: "?וואס איז דאס",trans: "Vos iz dos?", eng: "What is this?"}
            ];

            var images = ["images/sAleichem.jpg", "images/money.jpg", "images/BarMitzvah.jpg"];
            
            var answers = [{yid: "שלום אלייכעם", trans: "Sholem Aleichem", eng: "Shalom Aleichem"}, 
            {yid:"געלט",trans: "Gelt", eng:"Money"},
            {yid: "עבירה", trans: "Aveyre", eng: "Sin"}
            ];

            var articles = [{one: {yid: "דער", trans: "Der", eng: "The(m)"},
                two: {yid: "דאס", trans: "Dos", eng: "The(n)"},
                three: {yid: "א", trans: "A", eng: "A"},
                answer: {yid: "דער", trans: "Der", eng: "The(m)"}},
            {one: {yid: "דער", trans: "Der", eng: "The(m)"},
                two: {yid: "דאס", trans: "Dos", eng: "The(n)"},
                three: {yid: "די", trans: "Di", eng: "The(p)"},
                answer: {yid: "דאס", trans: "Dos", eng: "The(n)"}},
            {one: {yid: "דער", trans: "Der", eng: "The(m)"},
                two: {yid: "אן", trans: "An", eng: "A"},
                three: {yid: "א", trans: "A", eng: "A"},
                answer: {yid: "אן", trans: "An", eng: "A"}}
            ];
-Every set of flashcards will have these far arrays (ids, images, question, answers, and articles). They are parallel arrays and the 1st entry of one corresponds to the first of the other. 

-To create a card (following above format): 
        -Supply an id--this should be the next number starting from one.
        -Supply a question with a "yid," "trans," and "eng" version (as above). 
        -Supply an answer ("yid," "trans" and "eng" as well). Make sure it has the same index as the corresponding question.
        -Supply an image (make sure the image name is the correct path and corresponds to question).
        -Supply three articles per question, with their "yid," "trans" and "eng"; make sure to include a fourth article tagged "answer" (as above), which is merely a copy of the correct article choice. 

        If you wish to have only an image, without the question merely insert empty quatation marks (""). 


What to expect in the future:

-Flipping cards. 
-A java card genrating program to merge decks, make new ones, and to customize card appearance and features.
-cleaner code


A dank,
Rephoel 
