# ELT
WS testing

# SHELL
newman run https://raw.githubusercontent.com/arseniogalvao/ELT/master/ELT.json -e https://raw.githubusercontent.com/arseniogalvao/ELT/master/ELT_QA_environment.json -x --reporters cli,junit,html,json --reporter-junit-export report/outputfile.xml --reporter-html-export report/outputfile.html --reporter-json-export report/outputfile.json
