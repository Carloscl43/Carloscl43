document.getElementById("loginForm").addEventListener("submit", function(event) {
    event.preventDefault();
    var username = document.getElementById("username").value;
    var password = document.getElementById("password").value;
    
    var authenticated = true;

    if (authenticated) {
        document.getElementById("loginForm").style.display = "none";
        document.getElementById("consultaApis").style.display = "block";
    } else {
        alert("Usuário ou senha incorretos. Tente novamente.");
    }
});

document.getElementById("consultaCPF").addEventListener("click", function() {
});

document.getElementById("consultaCPF2").addEventListener("click", function() {
});
