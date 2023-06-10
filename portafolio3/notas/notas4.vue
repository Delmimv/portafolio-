<template>
    <div>
      <h2>¿Qué es la autenticación de la API?</h2>
      <p>
        Una capa de autenticación se utiliza comúnmente en aplicaciones para permitir a los usuarios iniciar y
        cerrar sesión, proteger la privacidad y limitar los permisos de los usuarios. La implementación de una capa de autenticación puede ser útil para proteger información confidencial y garantizar que solo los usuarios autorizados tengan acceso a los recursos protegidos.
      </p>
      
      <h3>Por qué implementar la autenticación basada en tokens</h3>
      <p>
        La Autenticación Basada en Token es una forma común de autenticación que funciona mediante el intercambio de tokens entre el cliente y el servidor. Los tokens se utilizan para validar la identidad del usuario y proporcionar acceso a los recursos protegidos. Esta forma de autenticación se considera segura porque los tokens pueden ser cifrados y firmados para evitar la manipulación o la suplantación de identidad.
      </p>
      <p>
        Sin embargo, es importante tener en cuenta que la seguridad de la Autenticación Basada en Token depende en gran medida de la forma en que se implemente. Por ejemplo, es importante utilizar algoritmos de cifrado y firma seguros para los tokens, así como garantizar que los tokens no sean almacenados en lugares vulnerables. Además, es importante considerar otros factores de seguridad, como la gestión de contraseñas y la protección contra ataques.
      </p>
      
      <h3>Token de seguridad</h3>
      <p>
        La Autenticación Basada en Token es una forma común de autenticación que funciona mediante el intercambio de tokens entre el cliente y el servidor. Los tokens se utilizan para validar la identidad del usuario y proporcionar acceso a los recursos protegidos. Esta forma de autenticación se considera segura porque los tokens pueden ser cifrados y firmados para evitar la manipulación o la suplantación de identidad.
      </p>
      <p>
        Sin embargo, es importante tener en cuenta que la seguridad de la Autenticación Basada en Token depende en gran medida de la forma en que se implemente. Por ejemplo, es importante utilizar algoritmos de cifrado y firma seguros para los tokens, así como garantizar que los tokens no sean almacenados en lugares vulnerables. Además, es importante considerar otros factores de seguridad, como la gestión de contraseñas y la protección contra ataques.
      </p>
      
      <h2>Rest API Laravel</h2>
      <p>
        Muchos puntos de conexión de la API REST necesitan autenticación o devuelven información adicional si se realiza el proceso de autenticación.
      </p>
      
      <p>
        Para autenticar la solicitud, envía un token en el encabezado Authorization de la solicitud. En el ejemplo siguiente, solo basta con reemplazar YOUR_TOKEN por una referencia al token.
      </p>
      
      <pre>
        <code>
          curl --request GET \
          --url "https://api.pets.com/pets" \
          --header "Authorization: Bearer YOUR-TOKEN"
        </code>
      </pre>
    
      <p>
      <h3>Implementación de autenticación</h3>
    </p>
      </div>