#How the script work 
1) The page will show your tableau dashboard and refresh every 15 seconds .
2) To refresh the dashboard you need to call tableau javascript api which name tableau-2.js. 
   For Tableau server , you can search and look for this file on the server you install tableau server (for multinode installation, it is in the initial node)
3) You need to replace your tableau dashboard URL on html script. 
4) There are the size of the dashboard specify on the script. Currently, I used 100% for hight and actual width for the dashboard. You can adjust it appropriately.