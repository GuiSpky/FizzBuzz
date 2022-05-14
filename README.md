<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="1_permuta.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
	<title>aula JS</title>
	<script type="text/javascript">
function numeros(){
				for (let i = 1; i <=100; ++i) {
					if (((i % 3) !== 0) && (i % 5) !== 0) {
						console.log(i)	
					}

					if ((i % 3) == 0 && (i % 5) !== 0)  {
						console.log('Fizz')
					}

					if ((i % 5 )== 0 && (i % 3) !== 0) {
						console.log('Buzz')
					}
					if (((i % 3) == 0) && (i % 5) == 0) {console.log('BuzzFizz')} 
				}
		}
</script>
</head>
<body>
  <button class="btn btn-primary" onclick="numeros()">attv 2</button>
</body>
</html>
