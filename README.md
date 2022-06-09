# repro_dotnet_maui_issue_7865
Simple code to show the problem

Note: Code uses images from imgur.com

see lines 16-20 in \repro_dotnet_maui_issue_7865\ImagePeriodicRefresh\ImagePeriodicRefresh\Components\Display.razor
replace with your own ones if those have expired

    private string [] SourceUrl = {
        "https://i.imgur.com/6FMRBcg.jpeg",
        "https://i.imgur.com/jZu3Nzw.jpeg",
        "https://i.imgur.com/hNJd0Fg.jpeg"
    };

# How to reproduce the issue:
1) Load the project into Visual Studio Preview
2) Just run the Windows debug version -> Debug/Any CPU/Windows machine
3) Wait...

