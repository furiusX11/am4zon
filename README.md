# am4zon
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inicio de Sesión en Amazon</title>
</head>
<body>
    <h1>Hola, tienes que iniciar sesión en tu cuenta de Amazon</h1>
    <button onclick="redirectToAmazon()">Iniciar Sesión en Amazon</button>

    <script>
        function redirectToAmazon() {
            // URL de Amazon para iniciar sesión
            var amazonLoginUrl = "https://www.amazon.com/ap/signin?openid.pape.max_auth_age=0&openid.return_to=https%3A%2F%2Fwww.amazon.com%2Fgp%2Fyour-account&openid.identity=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.assoc_handle=usflex&openid.mode=checkid_setup&openid.ns=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0&openid.claimed_id=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.ns.pape=http%3A%2F%2Fspecs.openid.net%2Fextensions%2Fpape%2F1.0&openid.pape.policy_uri=http%3A%2F%2Fspecs.openid.net%2Fextensions%2Fpape%2F1.0&openid.ns.oauth=http%3A%2F%2Fspecs.openid.net%2Fextensions%2Foauth%2F1.0&openid.oauth.consumer_key=AMZN&openid.oauth.scope=profile&openid.oauth.version=1.0";
            window.location.href = amazonLoginUrl;
        }
    </script>
</body>
</html>
