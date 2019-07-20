
    var JSON_asmaa = {
                        nama:'Asma Sundus Syarifah',
                        umur:26,
                        status_nikah:false,
                        hobi:['main basket di timezone','ngetik'],
                        list_school:[
                                {nama:'SDN 02 KIRIG', tahun:'2000-2008'},
                                {nama:'SMPIT ASSAIDIYYAH', tahun:'2008-2010'},
                                {nama:'MA SALAFIYYAH AHMAD SAID', tahun:'2011-2013'},
                                {nama:'SEKOLAH TINGGI EKONOMI DAN PERBANKAN ISLAM MR. SJAFRUDDIN PRAWIRANEGARA', tahun:'2013-2018'}
                        ]
                        skills:[
                            {nama:'coding', level:'beginner'}]
                        interest:'coding'
                   };
                    
    var nikah;
     
    if(JSON_asmaa.status_nikah){
        nikah = "sudah nikah";
    }else{
        nikah = "belum nikah";
    }
     
    document.write(JSON_asmaa.nama +" berumur "+JSON_asmaa.umur+" suka "+JSON_adi.hobi[0]+ " dan "+nikah+ "<br />");
    document.write("List nama : <br />");
    document.write("<ol>")
    for(var i=0; i<JSON_adi.list_school.length; i++){
        document.write("<li>" + JSON_adi.list_school[i].nama + " sekolah " + JSON_adi.list_school[i].tahun + "</li>");
    }
    document.write("</ol>")
    
    fungsi json pada rest api ialah mendirikan sebuah server rest api tiruan dengan usaha minimal
