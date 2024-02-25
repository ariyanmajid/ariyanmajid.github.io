body {
    margin: 0;
    padding: 60px 100px 20px;
}

.menu-list {
    float: right;
}

.menu-list li {
    display: inline-block;
    padding: 40px;
    margin: 25px 30px;
}

.dog {
    height: 150px;
}

header h1 {
    margin: 100px 0;
}

.round-white-box {
    margin-bottom: 80px; 
}

.main-flexbox {
    display: flex;  
    justify-content: space-between;
    align-items: center;
}

.main-textbox {
    width: 580px;
    padding: 0 50px;
    margin: 18px;  
}

.main-image {
    height: 400px;
    width: 1000px;
    margin: 18px;  
}

.main-button {
    display: inline-block;
    padding: 11px 0px;
    text-align: center;
    width: 340px;
    margin: 20px 0;
}

.main-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
/* Standard-Stile */
.main-flexbox {
    display: flex;  
    justify-content: space-between;
    align-items: flex-start; /* Elemente oben ausrichten */
    flex-wrap: wrap; /* Inhaltsboxen bei Bedarf umbrechen */
}

.main-textbox,
.main-image {
    flex: 1; /* Dynamische Größe für die Inhaltsboxen */
    margin: 18px; /* Abstand zwischen den Inhaltsboxen */
}

/* Stile für kleinere Bildschirme */
@media screen and (max-width: 768px) {
    .main-textbox,
    .main-image {
        flex-basis: 100%; /* Jede Inhaltsbox nimmt die volle Breite ein */
    }
}
