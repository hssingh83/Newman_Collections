
cd C:\Users\malay.p\AppData\Roaming\npm\newman.cmd
newman run "D:\\Malay\\Flag_Builder\\FB_API_Collection\APIs\\ezFlagBuilder .postman_collection.json" -e "D:\\Malay\\Flag_Builder\\FB_API_Collection\APIs\\Int.postman_environment.json" -g "D:\\Malay\\Flag_Builder\\FB_API_Collection\APIs\\My Workspace.postman_globals.json" --disable-unicode -–reporter-html-export:"D://Malay//Flag_Builder//FB_API_Collection//APIs//newman//myHTMLreport.html"




newman run C:\Users\hsingh\Desktop\newman\collection\Get_collection.json -e C:\Users\hsingh\Desktop\newman\collection\Standalone.postman_environment.json --insecure --global-var "url=http://localhost" --disable-unicode --reporters cli,junit,htmlextra \ 
--reporter-junit-export "newman/report.xml" \
--reporter-html-export \ "newman/report.html"