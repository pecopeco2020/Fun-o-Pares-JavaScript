# Fun-o-Pares-JavaScript
Exerc. 1 JS; Crie uma função que dado um intervalo (entre x e y) exiba todos número pares:

<html>
    <head></head>
    <body>
        <script>
                function pares (x, y){
                    var i;
                    for(i=x; i<=y; i++){
                        if (i%2 == '0'){
                            console.log(i);
                            i++;
                        }
                    }
                }
                pares(10, 50);
            
        </script>
    </body>
</html>

