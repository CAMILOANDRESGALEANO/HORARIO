HORARIO
=======

Horario ingenieria de sistemas


public class ventana extends javax.swing.JFrame {

    profesor pmate = new profesor();
    profesor carlos = new profesor();
    profesor eva = new profesor();
    profesor palgebra = new profesor();
    profesor pcatedra = new profesor();
    profesor pinglesl = new profesor();
    profesor joel = new profesor();
    profesor pedro = new profesor();
    materia matel = new materia();
    materia fingeniera = new materia();
    materia logica = new materia();
    materia algebra = new materia();
    materia catedra = new materia();
    materia inglesl= new materia();
    materia discretas = new materia();
    materia flogica = new materia();
    
   
    ///
    profesor pinglesll = new profesor();
    profesor jorger = new profesor();
    profesor jose = new profesor();
    profesor juaquin = new profesor();
    profesor pcomunicacionll = new profesor();
    profesor pconstitucion = new profesor();
    profesor jorgeq = new profesor();
    materia inglesll = new materia();
    materia singenieria = new materia();
    materia fprogramacion = new materia();
    materia fisical = new materia();
    materia comunicacionll = new materia();
    materia constitucion = new materia();
    materia matell = new materia();
    
    ///
    
    profesor juaquin1 = new profesor();
    profesor wilson =  new profesor();
    profesor joaquin =  new profesor();
    profesor bernabe =  new profesor();	
    profesor sotelo =  new profesor();
    profesor sotelo1 =  new profesor();
    profesor psociohumanistica = new profesor();
    materia fisicall =  new materia();
    materia programacionl =  new materia();
    materia elementos =  new materia();
    materia matelll =  new materia();
    materia progral =  new materia();
    materia estructuras =  new materia();
    materia sociohumanistica = new materia();
    
        //
    profesor bernabe1 = new profesor();
    profesor pingleslll = new profesor();
    profesor sotelo2 = new profesor();
    profesor sotelo3 = new profesor();
    profesor joaquin1 = new profesor();
    profesor eva1 = new profesor();
    profesor joel1 = new profesor();
    profesor joel2 = new profesor();
    materia matelv = new materia();
    materia ingleslll = new materia();
    materia programacionll = new materia();
    materia prograll = new materia();
    materia microprocesadores = new materia();
    materia tgs = new materia();
    materia fisicalll = new materia();
    materia discretas1 = new materia();
    
        public ventana() {
        initComponents();
            
            pmate.nombre="Profesor Matematica l";
            pmate.materia.nombrem="Matematica l";
            pmate.materia.horario="\nLunes 7-9\nMiercoles 7-9";
            matel.nombrem="Matematica l";
            matel.horario="\nLunes 7-9\nMiercoles 7-9";
            matel.profe=pmate;
            carlos.nombre="Profesor Carlos Vargas";
            carlos.materia.nombrem="Fundamentos de Ingeniera";
            carlos.materia.horario="\nLunes 7-9";
            fingeniera.nombrem="Fundamentos de Ingeniera";
            fingeniera.horario="\nLunes 7-9";
            fingeniera.profe=carlos;
            eva.nombre="Profesora Eva Patricia Vazques";
            eva.materia.nombrem="Logica y Algoritmia";
            eva.materia.horario="\nMartes 7-9\nViernes 7-9";
            logica.nombrem="Logica y Algoritmia";
            logica.horario="\nMartes 7-9\nViernes 7-9";
            logica.profe=eva;
            palgebra.nombre="Profesor Algebra Lineal";
            palgebra.materia.nombrem="Algebra Lineal";
            palgebra.materia.horario="\nMiercoles 9-11\nJueves 9-11\n Jueves 11-2";
            algebra.nombrem="Profesor Algebra Lineal";
            algebra.horario=palgebra.materia.horario;
            algebra.profe=palgebra;
            pcatedra.nombre="Profesor Catedra Udecina";
            pcatedra.materia.nombrem="Etica y Universalidad";
            pcatedra.materia.horario="\nJueves 7-9";
            catedra.nombrem="Etica y Universalidad";
            catedra.horario="\nJueves 7-9";
            catedra.profe=pcatedra;
            pinglesl.nombre="Profesor Ingles l";
            pinglesl.materia.nombrem="Ingles l";
            pinglesl.materia.horario="\nJueves 11-12\nViernes9-11";
            inglesl.nombrem="Ingles l";
            inglesl.horario="\nJueves 11-12\nViernes 9-11";
            inglesl.profe=pinglesl;
            joel.nombre="Profesor Joel Velasquez";
            joel.materia.nombrem="Matematicas Discretas";
            joel.materia.horario="\nViernes 12-3";
            discretas.nombrem="Matematicas Discretas";
            discretas.horario="\nViernes 12-3";
            discretas.profe=joel;
            pedro.nombre="Profesor Pedro Melendez";
            pedro.materia.nombrem="Fundamentos de Logica";
            pedro.materia.horario="\nMiercoles 2-4\nViernes 2-4";
            flogica.nombrem="Fundamentos de Logica\n";
            flogica.horario="\nMiercoles 2-4\nViernes 2-4\n";
            flogica.profe=pedro;
            //
            pinglesll.nombre="Profesor Ingles ll";
            pinglesll.materia.nombrem="Ingles ll";
            pinglesll.materia.horario="\nLunes 7-9\nMartes 7-8\n";
            inglesll.nombrem="Ingles ll";
            inglesll.horario=pinglesll.materia.horario;
            inglesll.profe=pinglesll;
            jorger.nombre="Profesor Jorge Reyes";
            jorger.materia.nombrem="Seminario de Ingenieria";
            jorger.materia.horario="\nLunes 9-12\n";
            singenieria.nombrem=jorger.materia.nombrem;
            singenieria.horario=jorger.materia.horario;
            singenieria.profe=jorger;
            jose.nombre="Profesor Jose Miguel Ojeda";
            jose.materia.nombrem="FUNDAMENTOS DE PROGRAMACION";
            jose.materia.horario="\nMartes 8-10\nJueves 8-10\n";
            fprogramacion.nombrem=jose.materia.nombrem;
            fprogramacion.horario=jose.materia.horario;
            fprogramacion.profe=jose;
            juaquin.nombre="Profesor Juaquin Rocha";
            juaquin.materia.nombrem="Fisica l";
            juaquin.materia.horario="\nMiercoles 7-9\nViernes 7-9\n";
            fisical.nombrem=juaquin.materia.nombrem;
            fisical.horario=juaquin.materia.horario;
            fisical.profe=juaquin;
            pcomunicacionll.nombre="Profesor Comunicacion ll";
            pcomunicacionll.materia.nombrem="Comunicacion ll";
            pcomunicacionll.materia.horario="\nMiercoles 9-12\n";
            comunicacionll.nombrem=pcomunicacionll.materia.nombrem;
            comunicacionll.horario=pcomunicacionll.materia.horario;
            comunicacionll.profe=pcomunicacionll;
            pconstitucion.nombre="Profesor Constitucion";
            pconstitucion.materia.nombrem="Constitucion Y Democracia";
            pconstitucion.materia.horario="\nJueves 7-8\n";
            constitucion.nombrem=pconstitucion.materia.nombrem;
            constitucion.horario=pconstitucion.materia.horario;


