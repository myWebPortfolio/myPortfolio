//Get parameter from URL
function getUrlParameter(parameter){
    var queryURL = window.location.search.substring(1);
    var variablesURL = queryURL.split('&');
    for (var i = 0; i < variablesURL.length; i++) 
    {
        var parameterURL = variablesURL[i].split('=');
        if (parameterURL[0] == parameter) 
        {
            return parameterURL[1];
        }
    }
}