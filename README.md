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
    
        //
     profesor esau = new profesor();
     profesor duvan = new profesor();
     profesor jorgeq1 = new profesor();
     profesor jose1 = new profesor();
     profesor esau1 = new profesor();
     profesor wilson1 = new profesor();
     profesor joel3 = new profesor();
     materia grafica = new materia();
     materia grafica1 = new materia();
     materia estadistica = new materia();
     materia sistemaso= new materia();
     materia sistemasi = new materia();
     materia especiales = new materia();
     materia fisicalv = new materia();
     //
     profesor nelly = new profesor();
     profesor esau2 = new profesor();
     profesor esau3 = new profesor();
     profesor carlos1 = new profesor();
     profesor sotelo4 = new profesor();
     profesor jose2 = new profesor();
     profesor maria = new profesor();
     profesor hector = new profesor ();
     materia economia = new materia();
     materia teoria = new materia();
     materia teoria1 = new materia();
     materia datos1= new materia();
     materia bases1 = new materia();
     materia sofware = new materia();
     materia contabilidad = new materia();
     materia metodos = new materia ();
     //
     profesor merchan = new profesor();
     profesor merchan1 = new profesor();
     profesor ascanio = new profesor();
     profesor pinvestigacion1 = new profesor();
     profesor duvan1 = new profesor();
     profesor jose3 = new profesor();
     profesor wilson2 = new profesor();
     profesor carlos2 = new profesor ();
     materia basesll = new materia();
     materia bases1ll = new materia();
     materia administracion = new materia();
     materia investigacionl= new materia();
     materia optimizacionl = new materia();
     materia sofwarell = new materia();
     materia datosll = new materia();
     materia electival = new materia ();
     //

    
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
            constitucion.profe=pconstitucion;
            jorgeq.nombre="Profesor Jorge Quevedo";
            jorgeq.materia.nombrem="Matematicas ll";
            jorgeq.materia.horario="\nMiercoles 3-5\nJueves 3-5\n";
            matell.nombrem=jorgeq.materia.nombrem;
            matell.horario=jorgeq.materia.horario;
            matell.profe=jorgeq;
            //
            juaquin1.nombre=juaquin.nombre;
            juaquin1.materia.nombrem="Fisica ll";
            juaquin1.materia.horario="\nLunes 7-9\nJueves 7-9\n";
            fisicall.nombrem=juaquin1.materia.nombrem;
            fisicall.horario=juaquin1.materia.horario;
            fisicall.profe=juaquin1;
            wilson.nombre="Profesor Wilson Gordillo";
            wilson.materia.nombrem="Programacion l";
            wilson.materia.horario="\nLunes 9-11\nMiercoles 9-11\n";
            programacionl.nombrem=wilson.materia.nombrem;
            programacionl.horario=wilson.materia.horario;
            programacionl.profe=wilson;
            joaquin.nombre="Profesor Joaquin Ariza";
            joaquin.materia.nombrem="Elementos de computador";
            joaquin.materia.horario="\nMartes 7-10\n";
            elementos.nombrem=joaquin.materia.nombrem;
            elementos.horario=joaquin.materia.horario;
            elementos.profe=joaquin;
            bernabe.nombre="Profesor Bernabe Buitrago";
            bernabe.materia.nombrem="Matematicas lll";
            bernabe.materia.horario="\nMartes 3-6\nMiercoles 7-9\n";
            matelll.nombrem=bernabe.materia.nombrem;
            matelll.horario=bernabe.materia.horario;
            matelll.profe=bernabe;
            sotelo.nombre="Profesor Fernando Sotelo";
            sotelo.materia.nombrem="Estructuras de Informacion";
            sotelo.materia.horario="\nMiercoles 11-1\nJueves 9-11\n";
            estructuras.nombrem=sotelo.materia.nombrem;
            estructuras.horario=sotelo.materia.horario;
            estructuras.profe=sotelo;
            sotelo1.nombre=sotelo.nombre;
            sotelo1.materia.nombrem="Programacion l";
            sotelo1.materia.horario="\nLUNES 8-10\nMARTES 8-10\n";
            progral.nombrem=sotelo1.materia.nombrem;
            progral.horario=sotelo1.materia.horario;
            progral.profe=sotelo1;
            psociohumanistica.nombre="Profesor Electiva SocioHumanistica";
            psociohumanistica.materia.nombrem="Electiva Sociohumanistica";
            psociohumanistica.materia.horario="\nViernes 7-10\n";
            sociohumanistica.nombrem="Electiva Sociohumanistica";
            sociohumanistica.horario="\nViernes 7-10\n";
            sociohumanistica.profe=psociohumanistica;
            //
            bernabe1.nombre=bernabe.nombre;
            bernabe1.materia.nombrem="Ecuaciones Diferenciales";
            bernabe1.materia.horario="\nLunes 7-9\nJueves 7-9\n";
            matelv.nombrem=bernabe1.materia.nombrem;
            matelv.horario=bernabe1.materia.horario;
            matelv.profe=bernabe1;
            pingleslll.nombre="Profesor de Ingles lll";
            pingleslll.materia.nombrem="Ingles lll";
            pingleslll.materia.horario="\nLunes 9-11\nMartes 10-11";
            ingleslll.nombrem=pingleslll.materia.nombrem;
            ingleslll.horario=pingleslll.materia.horario;
            ingleslll.profe=pingleslll;
            sotelo2.nombre=sotelo.nombre;
            sotelo2.materia.nombrem="Programacion ll";
            sotelo2.materia.horario="\nLUNES 11-1\nMARTES 11-1\n";
            programacionll.nombrem=sotelo2.materia.nombrem;
            programacionll.horario=sotelo2.materia.horario;
            programacionll.profe=sotelo2;
            sotelo3.nombre=sotelo.nombre;
            sotelo3.materia.nombrem="Programacion ll";
            sotelo3.materia.horario="\nJueves 11-1\nViernes 11-1\n";
            prograll.nombrem=sotelo3.materia.nombrem;
            prograll.horario=sotelo3.materia.horario;
            prograll.profe=sotelo3;
            joaquin1.nombre=joaquin.nombre;
            joaquin1.materia.nombrem="Microprocesadores";
            joaquin1.materia.horario="\nJueves 10-12\nViernes 7-9\n";
            microprocesadores.nombrem=joaquin1.materia.nombrem;
            microprocesadores.horario=joaquin1.materia.horario;
            microprocesadores.profe=joaquin1;
            eva1.nombre=eva.nombre;
            eva1.materia.nombrem="Teoria General De Sistemas";
            eva1.materia.horario="\nViernes 9-12\n";
            tgs.nombrem=eva1.materia.nombrem;
            tgs.horario=eva1.materia.horario;
            tgs.profe=eva1;
            joel1.nombre=joel.nombre;
            joel1.materia.nombrem="Fisica lll";
            joel1.materia.horario="\nMiercoles 2-4\nJueves 2-4\n";
            fisicalll.nombrem=joel1.materia.nombrem;
            fisicalll.horario=joel1.materia.horario;
            fisicalll.profe=joel1;
            joel2.nombre=joel.nombre;
            joel2.materia.nombrem="Matematicas Discretas";
            joel2.materia.horario="\nViernes 4-7\n";
            discretas1.nombrem=joel2.materia.nombrem;
            discretas1.horario=joel2.materia.horario;
            discretas1.profe=joel2;
            //
            esau.nombre="Profesor Esau Paloma";
            esau.materia.nombrem="Computacion Grafica";
            esau.materia.horario="\nLunes 7-9\nViernes 12-2";
            grafica.nombrem=esau.materia.nombrem;
            grafica.horario=esau.materia.horario;
            grafica.profe=esau;
            esau1.nombre=esau.nombre;
            esau1.materia.nombrem=esau.materia.nombrem;
            esau1.materia.horario="\nMartes 11-1\nMiercoles 7-9";
            grafica1.nombrem=esau.materia.nombrem;
            grafica1.horario=esau1.materia.horario;
            grafica1.profe=esau1;
            duvan.nombre="Profesor Duvan Ordoñez";
            duvan.materia.nombrem="Estadistica Y Probabilidad";
            duvan.materia.horario="\nLunes 9-12";
            estadistica.nombrem=duvan.materia.nombrem;
            estadistica.horario=duvan.materia.horario;
            estadistica.profe=duvan;
            wilson1.nombre=wilson.nombre;
            wilson1.materia.nombrem="Sistemas Operativos";
            wilson1.materia.horario="\nLunes 2-4\nJueves 2-4";
            sistemaso.nombrem=wilson1.materia.nombrem;
            sistemaso.horario=wilson1.materia.horario;
            sistemaso.profe=wilson1;
            jorgeq1.nombre=jorgeq.nombre;
            jorgeq1.materia.nombrem="Matematicas Especiales";
            jorgeq1.materia.horario="\nMartes 7-9\nMiercoles 7-9";
            especiales.nombrem=jorgeq1.materia.nombrem;
            especiales.horario=jorgeq1.materia.horario;
            especiales.profe=jorgeq1;
            jose1.nombre=jose.nombre;
            jose1.materia.nombrem="Sistemas de Informacion";
            jose1.materia.horario="\nMartes 2-4\nJueves 10-12";
            sistemasi.nombrem=jose1.materia.nombrem;
            sistemasi.horario=jose1.materia.horario;
            sistemasi.profe=jose1;
            joel3.nombre=joel.nombre;
            joel3.materia.nombrem="Fisica lV";
            joel3.materia.horario="\nJueves 8-10\nViernes 8-10";
            fisicalv.nombrem=joel3.materia.nombrem;
            fisicalv.horario=joel3.materia.horario;
            fisicalv.profe=joel3;
            //
            nelly.nombre="Profesora Nelly Gonzales";
            nelly.materia.nombrem="Economia";
            nelly.materia.horario="\nLunes 7-10";
            economia.nombrem=nelly.materia.nombrem;
            economia.horario=nelly.materia.horario;
            economia.profe=nelly;
            esau2.nombre=esau.nombre;
            esau2.materia.nombrem="Teoria de Control";
            esau2.materia.horario="\nLunes 11-1\nMiercoles 9-11";
            teoria.nombrem=esau2.materia.nombrem;
            teoria.horario=esau2.materia.horario;
            teoria.profe=esau2;
            esau3.nombre=esau.nombre;
            esau3.materia.nombrem="Teoria de Control";
            esau3.materia.horario="\nLunes 9-11\nViernes 10-12";
            teoria1.nombrem=esau3.materia.nombrem;
            teoria1.horario=esau3.materia.horario;
            teoria1.profe=esau3;
            carlos1.nombre=carlos.nombre;
            carlos1.materia.nombrem="Comunicacion de datos 1";
            carlos1.materia.horario="\nMartes 7-9\nJueves 7-9";
            datos1.nombrem=carlos1.materia.nombrem;
            datos1.horario=carlos1.materia.horario;
            datos1.profe=carlos1;
            sotelo4.nombre=sotelo.nombre;
            sotelo4.materia.nombrem="Bases de Datos l";
            sotelo4.materia.horario="\nMiercoles 7-9\nViernes 7-9";
            bases1.nombrem=sotelo4.materia.nombrem;
            bases1.horario=sotelo4.materia.horario;
            bases1.profe=sotelo4;
            jose2.nombre=jose.nombre;
            jose2.materia.nombrem="Ingenieria de Sofware";
            jose2.materia.horario="\nMiercoles 11-1\nJueves 12-2";
            sofware.nombrem=jose2.materia.nombrem;
            sofware.horario=jose2.materia.horario;
            sofware.profe=jose2;
            maria.nombre="Profesora Maria Velasquez";
            maria.materia.nombrem="Contabilidad";
            maria.materia.horario="\nJueves 9-12";
            contabilidad.nombrem=maria.materia.nombrem;
            contabilidad.horario=maria.materia.horario;
            contabilidad.profe=maria;
            hector.nombre="Profesor Hector Romero";
            hector.materia.nombrem="Metodos Numericos";
            hector.materia.horario="\nViernes 2-5";
            metodos.nombrem=hector.materia.nombrem;
            metodos.horario=hector.materia.horario;
            metodos.profe=hector;
            //
            merchan.nombre="Profesora Esperanza Merchan";
            merchan.materia.nombrem="Bases de Datos ll";
            merchan.materia.horario="\nLunes 7-9\nMartes 7-9";
            basesll.nombrem=merchan.materia.nombrem;
            basesll.horario=merchan.materia.horario;
            basesll.profe=merchan;
            merchan1.nombre=merchan.nombre;
            merchan1.materia.nombrem=merchan.materia.nombrem;
            merchan1.materia.horario="\nJueves 2-4\nViernes 2-4";
            bases1ll.nombrem=merchan1.materia.nombrem;
            bases1ll.horario=merchan1.materia.horario;
            bases1ll.profe=merchan1;
            ascanio.nombre="Profesor Ascanio Horta";
            ascanio.materia.nombrem="Administracion Y Gestion";
            ascanio.materia.horario="\nLunes 10-1";
            administracion.nombrem=ascanio.materia.nombrem;
            administracion.horario=ascanio.materia.horario;
            administracion.profe=ascanio;
            pinvestigacion1.nombre="Profesor Investigacion l";
            pinvestigacion1.materia.nombrem="Investigacion l";
            pinvestigacion1.materia.horario="\nMartes 9-11";
            investigacionl.nombrem=pinvestigacion1.materia.nombrem;
            investigacionl.horario=pinvestigacion1.materia.horario;
            investigacionl.profe=pinvestigacion1;
            duvan1.nombre=duvan.nombre;
            duvan1.materia.nombrem="Optimizacion l";
            duvan1.materia.horario="\nMiercoles 7-9\nJueves 7-9";
            optimizacionl.nombrem=duvan1.materia.nombrem;
            optimizacionl.horario=duvan1.materia.horario;
            optimizacionl.profe=duvan1;
            jose3.nombre=jose.nombre;
            jose3.materia.nombrem="Ingenieria de Sofware ll";
            jose3.materia.horario="\nMiercoles 9-11\nJueves de 2-4";
            sofwarell.nombrem=jose3.materia.nombrem;
            sofwarell.horario=jose3.materia.horario;
            sofwarell.profe=jose3;
            wilson2.nombre=wilson.nombre;
            wilson2.materia.nombrem="Comunicacion de Datos ll";
            wilson2.materia.horario="\nMiercoles 12-2\nJueves9-11";
            datosll.nombrem=wilson2.materia.nombrem;
            datosll.horario=wilson2.materia.horario;
            datosll.profe=wilson2;
            carlos2.nombre=carlos.nombre;
            carlos2.materia.nombrem="Electiva Basica De Ingenieria l";
            carlos2.materia.horario="\nViernes 7-10";
            electival.nombrem=carlos2.materia.nombrem;
            electival.horario=carlos2.materia.horario;
            electival.profe=carlos2;
            //
            oscar.nombre="Profesor Oscar Bachiller";
            oscar.materia.nombrem="Inteligencia Artificial";
            oscar.materia.horario="\nLunes 7-9\nMiercoles 7-9";
            inteligencia.nombrem=oscar.materia.nombrem;
            inteligencia.horario=oscar.materia.horario;
            inteligencia.profe=oscar;
            ascanio1.nombre=ascanio.nombre;
            ascanio1.materia.nombrem="Planeacion Estrategica";
            ascanio1.materia.horario="\nMartes 7-10";
            planeacion.nombrem=ascanio1.materia.nombrem;
            planeacion.horario=ascanio1.materia.horario;
            planeacion.profe=ascanio1;
            pinvestigacionll.nombre="Profesor Investigacion ll";
            pinvestigacionll.materia.nombrem="Investigacion ll";
            pinvestigacionll.materia.horario="\nJueves 7-9";
            investigacionll.nombrem=pinvestigacionll.materia.nombrem;
            investigacionll.horario=pinvestigacionll.materia.horario;
            investigacionll.profe=pinvestigacionll;
            duvan2.nombre=duvan.nombre;
            duvan2.materia.nombrem="Optimizacion ll";
            duvan2.materia.horario="\nMartes 11-1\n Miercoles 9-11";
            optimizacionll.nombrem=duvan2.materia.nombrem;
            optimizacionll.horario=duvan2.materia.horario;
            optimizacionll.profe=duvan2;
            pedro1.nombre=pedro.nombre;
            pedro1.materia.nombrem="Electiva Basica De Ingenieria ll";
            pedro1.materia.horario="\nMartes 2-4";
            electivall.nombrem=pedro1.materia.nombrem;
            electivall.horario=pedro1.materia.horario;
            electivall.profe=pedro1;
            duvan3.nombre=duvan.nombre;
            duvan3.materia.nombrem="Formulacion y Evaluacion De Proyectos";
            duvan3.materia.horario="\nJueves 10-1";
            formulacion.nombrem=duvan3.materia.nombrem;
            formulacion.horario=duvan3.materia.horario;
            formulacion.profe=duvan3;
            //
            wilson3.nombre=wilson.nombre;
            wilson3.materia.nombrem="Electiva Profesional ll";
            wilson3.materia.horario="\nLunes 7-9\nMiercoles 7-9";
            electivapll.nombrem=wilson3.materia.nombrem;
            electivapll.horario=wilson3.materia.horario;
            electivapll.profe=wilson3;
            castillo.nombre="Profesor Gustavo Castillo";
            castillo.materia.nombrem="Electiva Profesional ll";
            castillo.materia.horario="\nLunes 2-4\nJueves 2-4";
            electivap1ll.nombrem=castillo.materia.nombrem;
            electivap1ll.horario=castillo.materia.horario;
            electivap1ll.profe=castillo;
            marcia.nombre="Profesor Marcia Pulido";
            marcia.materia.nombrem="Electiva Profesional l";
            marcia.materia.horario="\nMiercoles 2-4\nViernes 2-4";
            electivapl.nombrem=marcia.materia.nombrem;
            electivapl.horario=marcia.materia.horario;
            electivapl.profe=marcia;
            merchan2.nombre=merchan.nombre;
            merchan2.materia.nombrem="Electiva Profesional l";
            merchan2.materia.horario="\nMiercoles 9-11\nViernes 7-9";
            electivap1l.nombrem=merchan2.materia.nombrem;
            electivap1l.horario=merchan2.materia.horario;
            electivap1l.profe=merchan2;
            joaquin2.nombre=joaquin.nombre;
            joaquin2.materia.nombrem="Auditoria de Sistemas";
            joaquin2.materia.horario="\nMartes 10-1";
            auditoria.nombrem=joaquin2.materia.nombrem;
            auditoria.horario=joaquin2.materia.horario;
            auditoria.profe=joaquin2;
            duvan4.nombre=duvan.nombre;
            duvan4.materia.nombrem="Modelacion";
            duvan4.materia.horario="\nLunes 4-6\nMiercoles 11-1";
            modelacion.nombrem=duvan4.materia.nombrem;
            modelacion.horario=duvan4.materia.horario;
            modelacion.profe=duvan4;
            oscar1.nombre=oscar.nombre;
            oscar1.materia.nombrem="Investigacion lll";
            oscar1.materia.horario="\nJueves 9-12";
            investigacionlll.nombrem=oscar1.materia.nombrem;
            investigacionlll.horario=oscar1.materia.horario;
            investigacionlll.profe=oscar1;
            carlos3.nombre=carlos.nombre;
            carlos3.materia.nombrem="Gerencia Informatica";
            carlos3.materia.horario="\nViernes 10-1";
            gerencia.nombrem=carlos3.materia.nombrem;
            gerencia.horario=carlos3.materia.horario;
            gerencia.profe=carlos3;
            //
            carlos4.nombre=carlos.nombre;
            carlos4.materia.nombrem="Electiva Profesional lll";
            carlos4.materia.horario="\nLunes 7-9\nJueves 11-1";
            electivaplll.nombrem=carlos4.materia.nombrem;
            electivaplll.horario=carlos4.materia.horario;
            electivaplll.profe=carlos4;
            marcia1.nombre=marcia.nombre;
            marcia1.materia.nombrem="Proyecto de Grado";
            marcia1.materia.horario="\nLunes 12-1\nJueves 9-11";
            proyecto.nombrem=marcia1.materia.nombrem;
            proyecto.horario=marcia1.materia.horario;
            proyecto.profe=marcia1;
            esau4.nombre=esau.nombre;
            esau4.materia.nombrem="Electiva Profesional lV";
            esau4.materia.horario="\nMartes 8-10\nJueves 7-9";
            electivaplv.nombrem=esau4.materia.nombrem;
            electivaplv.horario=esau4.materia.horario;
            electivaplv.profe=esau4;
            jose4.nombre=jose.nombre;
            jose4.materia.nombrem="Gestion Tegnologica";
            jose4.materia.horario="\nMartes 10-1";
            gestion.nombrem=jose4.materia.nombrem;
            gestion.horario=jose4.materia.horario;
            gestion.profe=jose4;
            jorger1.nombre=jorger.nombre;
            jorger1.materia.nombrem="Legislacion de Ingenieria";
            jorger1.materia.horario="Viernes 10-1";
            legislacion.nombrem=jorger1.materia.nombrem;
            legislacion.horario=jorger1.materia.horario;
            legislacion.profe=jorger1;
            botero.nombre="Profesor Allfonso Botero";
            botero.materia.nombrem="Proyecto de Grado";
            botero.materia.horario="\nLunes 12-2\nJueves 9-11";
            proyecto1.nombrem=botero.materia.nombrem;
            proyecto1.horario=botero.materia.horario;
            proyecto1.profe=botero;
            eva2.nombre=eva.nombre;
            eva2.materia.nombrem="Etica para Ingenieros";
            eva2.materia.horario="\nMiercoles 7-10";
            etica.nombrem=eva2.materia.nombrem;
            etica.horario=eva2.materia.horario;
            etica.profe=eva2;
            
    }

    private void initComponents() {

        jScrollPane1 = new javax.swing.JScrollPane();
        tex = new javax.swing.JTextArea();
        jMenuBar1 = new javax.swing.JMenuBar();
        jMenu1 = new javax.swing.JMenu();
        jMenu3 = new javax.swing.JMenu();
        jMenu7 = new javax.swing.JMenu();
        jMenuItem73 = new javax.swing.JMenuItem();
        jMenuItem74 = new javax.swing.JMenuItem();
        jMenuItem75 = new javax.swing.JMenuItem();
        jMenuItem84 = new javax.swing.JMenuItem();
        jMenuItem85 = new javax.swing.JMenuItem();
        jMenuItem93 = new javax.swing.JMenuItem();
        jMenuItem94 = new javax.swing.JMenuItem();
        jMenuItem95 = new javax.swing.JMenuItem();
        jMenuItem1 = new javax.swing.JMenuItem();
        jMenuItem3 = new javax.swing.JMenuItem();
        jMenuItem4 = new javax.swing.JMenuItem();
        jMenuItem5 = new javax.swing.JMenuItem();
        jMenuItem6 = new javax.swing.JMenuItem();
        jMenuItem7 = new javax.swing.JMenuItem();
        jMenuItem8 = new javax.swing.JMenuItem();
        jMenuItem9 = new javax.swing.JMenuItem();
        jMenuItem18 = new javax.swing.JMenuItem();
        jMenuItem19 = new javax.swing.JMenuItem();
        jMenuItem20 = new javax.swing.JMenuItem();
        jMenuItem21 = new javax.swing.JMenuItem();
        jMenuItem22 = new javax.swing.JMenuItem();
        jMenuItem23 = new javax.swing.JMenuItem();
        jMenuItem24 = new javax.swing.JMenuItem();
        jMenuItem33 = new javax.swing.JMenuItem();
        jMenuItem34 = new javax.swing.JMenuItem();
        jMenuItem35 = new javax.swing.JMenuItem();
        jMenuItem36 = new javax.swing.JMenuItem();
        jMenuItem37 = new javax.swing.JMenuItem();
        jMenuItem45 = new javax.swing.JMenuItem();
        jMenuItem53 = new javax.swing.JMenuItem();
        jMenuItem54 = new javax.swing.JMenuItem();
        jMenuItem56 = new javax.swing.JMenuItem();
        jMenuItem57 = new javax.swing.JMenuItem();
        jMenuItem58 = new javax.swing.JMenuItem();
        jMenu4 = new javax.swing.JMenu();
        jMenu6 = new javax.swing.JMenu();
        jMenu8 = new javax.swing.JMenu();
        jMenuItem88 = new javax.swing.JMenuItem();
        jMenuItem89 = new javax.swing.JMenuItem();
        jMenuItem90 = new javax.swing.JMenuItem();
        jMenuItem91 = new javax.swing.JMenuItem();
        jMenuItem96 = new javax.swing.JMenuItem();
        jMenuItem97 = new javax.swing.JMenuItem();
        jMenuItem98 = new javax.swing.JMenuItem();
        jMenuItem99 = new javax.swing.JMenuItem();
        jMenuItem100 = new javax.swing.JMenuItem();
        jMenuItem101 = new javax.swing.JMenuItem();
        jMenuItem103 = new javax.swing.JMenuItem();
        jMenuItem104 = new javax.swing.JMenuItem();
        jMenuItem105 = new javax.swing.JMenuItem();
        jMenuItem106 = new javax.swing.JMenuItem();
        jMenuItem107 = new javax.swing.JMenuItem();
        jMenuItem108 = new javax.swing.JMenuItem();
        jMenuItem50 = new javax.swing.JMenuItem();
        jMenuItem51 = new javax.swing.JMenuItem();
        jMenuItem59 = new javax.swing.JMenuItem();
        jMenuItem60 = new javax.swing.JMenuItem();
        jMenuItem61 = new javax.swing.JMenuItem();
        jMenuItem62 = new javax.swing.JMenuItem();
        jMenuItem63 = new javax.swing.JMenuItem();
        jMenuItem64 = new javax.swing.JMenuItem();
        jMenuItem65 = new javax.swing.JMenuItem();
        jMenuItem66 = new javax.swing.JMenuItem();
        jMenuItem67 = new javax.swing.JMenuItem();
        jMenuItem68 = new javax.swing.JMenuItem();
        jMenuItem69 = new javax.swing.JMenuItem();
        jMenuItem70 = new javax.swing.JMenuItem();
        jMenuItem71 = new javax.swing.JMenuItem();
        jMenuItem76 = new javax.swing.JMenuItem();
        jMenuItem77 = new javax.swing.JMenuItem();
        jMenuItem78 = new javax.swing.JMenuItem();
        jMenuItem79 = new javax.swing.JMenuItem();
        jMenuItem80 = new javax.swing.JMenuItem();
        jMenuItem81 = new javax.swing.JMenuItem();
        jMenuItem82 = new javax.swing.JMenuItem();
        jMenuItem86 = new javax.swing.JMenuItem();
        jMenuItem87 = new javax.swing.JMenuItem();
        jMenuItem2 = new javax.swing.JMenuItem();
        jMenuItem10 = new javax.swing.JMenuItem();
        jMenuItem11 = new javax.swing.JMenuItem();
        jMenuItem12 = new javax.swing.JMenuItem();
        jMenuItem13 = new javax.swing.JMenuItem();
        jMenuItem14 = new javax.swing.JMenuItem();
        jMenuItem15 = new javax.swing.JMenuItem();
        jMenuItem16 = new javax.swing.JMenuItem();
        jMenuItem25 = new javax.swing.JMenuItem();
        jMenuItem26 = new javax.swing.JMenuItem();
        jMenuItem27 = new javax.swing.JMenuItem();
        jMenuItem28 = new javax.swing.JMenuItem();
        jMenuItem29 = new javax.swing.JMenuItem();
        jMenuItem30 = new javax.swing.JMenuItem();
        jMenuItem31 = new javax.swing.JMenuItem();
        jMenuItem38 = new javax.swing.JMenuItem();
        jMenuItem39 = new javax.swing.JMenuItem();
        jMenuItem40 = new javax.swing.JMenuItem();
        jMenuItem41 = new javax.swing.JMenuItem();
        jMenuItem42 = new javax.swing.JMenuItem();
        jMenuItem43 = new javax.swing.JMenuItem();
        jMenuItem46 = new javax.swing.JMenuItem();
        jMenuItem47 = new javax.swing.JMenuItem();
        jMenuItem48 = new javax.swing.JMenuItem();
        jMenuItem49 = new javax.swing.JMenuItem();
        jMenu5 = new javax.swing.JMenu();
        jMenuItem17 = new javax.swing.JMenuItem();
        jMenuItem32 = new javax.swing.JMenuItem();
        jMenuItem44 = new javax.swing.JMenuItem();
        jMenuItem52 = new javax.swing.JMenuItem();
        jMenuItem55 = new javax.swing.JMenuItem();
        jMenuItem72 = new javax.swing.JMenuItem();
        jMenuItem83 = new javax.swing.JMenuItem();
        jMenuItem92 = new javax.swing.JMenuItem();
        jMenuItem102 = new javax.swing.JMenuItem();
        jMenuItem109 = new javax.swing.JMenuItem();
        jMenu2 = new javax.swing.JMenu();
        jMenuItem110 = new javax.swing.JMenuItem();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        tex.setColumns(20);
        tex.setRows(5);
        jScrollPane1.setViewportView(tex);
        
        
                jMenu1.setText("MENU");

        jMenu3.setText("PROFESOR");
        jMenu3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenu3ActionPerformed(evt);
            }
        });

        jMenu7.setText("MAS");

        jMenuItem73.setText("Prof. Esperanza M.");
        jMenuItem73.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem73ActionPerformed(evt);
            }
        });
        jMenu7.add(jMenuItem73);

        jMenuItem74.setText("Prof. Ascanio H.");
        jMenuItem74.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem74ActionPerformed(evt);
            }
        });
        jMenu7.add(jMenuItem74);

        jMenuItem75.setText("Prof. Investigacion l");
        jMenuItem75.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem75ActionPerformed(evt);
            }
        });
        jMenu7.add(jMenuItem75);

        jMenuItem84.setText("Prof. Oscar B.");
        jMenuItem84.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem84ActionPerformed(evt);
            }
        });
        jMenu7.add(jMenuItem84);
        
                jMenuItem85.setText("Prof. Investigacion ll");
        jMenuItem85.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem85ActionPerformed(evt);
            }
        });
        jMenu7.add(jMenuItem85);

        jMenuItem93.setText("Prof. Gustavo C.");
        jMenuItem93.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem93ActionPerformed(evt);
            }
        });
        jMenu7.add(jMenuItem93);

        jMenuItem94.setText("Prof. Marcia P.");
        jMenuItem94.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem94ActionPerformed(evt);
            }
        });

        jMenu7.add(jMenuItem94);

        jMenuItem95.setText("Prof. Alfonso B.");
        jMenuItem95.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem95ActionPerformed(evt);
            }
        });
        jMenu7.add(jMenuItem95);

        jMenu3.add(jMenu7);

        jMenuItem1.setText("Prof. Matematicas l");
        jMenuItem1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem1ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem1);

        jMenuItem3.setText("Prof. Carlos V.");
        jMenuItem3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem3ActionPerformed(evt);
            }
        });
        
        jMenu3.add(jMenuItem3);

        jMenuItem4.setText("Prof. Eva V.");
        jMenuItem4.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem4ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem4);

        jMenuItem5.setText("Prof. Algebra L.");
        jMenuItem5.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem5ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem5);

        jMenuItem6.setText("Prof. Catedra U.");
        jMenuItem6.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem6ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem6);

        jMenuItem7.setText("Prof. Ingles l");
        jMenuItem7.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem7ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem7);

        jMenuItem8.setText("Prof. Joel V.");
        jMenuItem8.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem8ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem8);

        jMenuItem9.setText("Prof. Pedro M.");
        jMenuItem9.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem9ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem9);

        jMenuItem18.setText("Prof. Ingles ll");
        jMenuItem18.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem18ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem18);

        jMenuItem19.setText("Prof. Jorge R.");
        jMenuItem19.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem19ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem19);

        jMenuItem20.setText("Prof. Jose O.");
        jMenuItem20.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem20ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem20);

        jMenuItem21.setText("Prof. Juaquin R.");
        jMenuItem21.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem21ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem21);

        jMenuItem22.setText("Prof. Comunicacion ll");
        jMenuItem22.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem22ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem22);

        jMenuItem23.setText("Prof. Constitucion");
        jMenuItem23.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem23ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem23);

        jMenuItem24.setText("Prof. Jorge Q.");
        jMenuItem24.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem24ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem24);

        jMenuItem33.setText("Prof. Wilson G.");
        jMenuItem33.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem33ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem33);

        jMenuItem34.setText("Prof. Joaquin A.");
        jMenuItem34.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem34ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem34);

        jMenuItem35.setText("Prof. Bernabe B.");
        jMenuItem35.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem35ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem35);

        jMenuItem36.setText("Prof. Fernando S. ");
        jMenuItem36.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem36ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem36);

        jMenuItem37.setText("Prof. Electiva S.");
        jMenuItem37.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem37ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem37);

        jMenuItem45.setText("Prof. Ingles lll");
        jMenuItem45.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem45ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem45);

        jMenuItem53.setText("Prof. Esau P.");
        jMenuItem53.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem53ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem53);

        jMenuItem54.setText("Prof. Duvan O.");
        jMenuItem54.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem54ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem54);

        jMenuItem56.setText("Prof. Nelly G.");
        jMenuItem56.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem56ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem56);

        jMenuItem57.setText("Prof. Maria V.");
        jMenuItem57.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem57ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem57);

        jMenuItem58.setText("Prof Hector R.");
        jMenuItem58.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem58ActionPerformed(evt);
            }
        });
        jMenu3.add(jMenuItem58);

        jMenu1.add(jMenu3);

        jMenu4.setText("MATERIA");

        jMenu6.setText("MAS");

        jMenu8.setText("MAS");

        jMenuItem88.setText("Investigacion ll");
        jMenuItem88.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem88ActionPerformed(evt);
            }
        });
        jMenu8.add(jMenuItem88);

        jMenuItem89.setText("Optimizacion ll");
        jMenuItem89.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem89ActionPerformed(evt);
            }
        });
        jMenu8.add(jMenuItem89);

        jMenuItem90.setText("Electiva Basica De Ingenieria ll");
        jMenuItem90.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem90ActionPerformed(evt);
            }
        });
        jMenu8.add(jMenuItem90);

        jMenuItem91.setText("Formulacion y Evaluacion de Proyectos");
        jMenuItem91.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem91ActionPerformed(evt);
            }
        });
        jMenu8.add(jMenuItem91);

        jMenuItem96.setText("Electiva Profesional ll");
        jMenuItem96.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem96ActionPerformed(evt);
            }
        });
        jMenu8.add(jMenuItem96);

        jMenuItem97.setText("Electiva Profesional l");
        jMenuItem97.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem97ActionPerformed(evt);
            }
        });
        jMenu8.add(jMenuItem97);

        jMenuItem98.setText("Auditoria De Sistemas");
        jMenuItem98.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem98ActionPerformed(evt);
            }
        });
        jMenu8.add(jMenuItem98);

        jMenuItem99.setText("Modelacion");
        jMenuItem99.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem99ActionPerformed(evt);
            }
        });
        jMenu8.add(jMenuItem99);

        jMenuItem100.setText("Investigacion lll");
        jMenuItem100.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem100ActionPerformed(evt);
            }
        });
        jMenu8.add(jMenuItem100);

        jMenuItem101.setText("Gerencia Informatica");
        jMenuItem101.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jMenuItem101ActionPerformed(evt);
            }
        });







