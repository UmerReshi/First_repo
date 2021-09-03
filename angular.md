intro to Angular, Modules, Type script, Java Script, 

1 Angular -> framework

2 Angular Modules -> routing files -> components =  html files, TS files(relevent logic of component), css files

3 Javascript
              Class(Blueprint which contains structure) 
              Objects (Live entity in memory that has its behaviour ) created by using new operator
              var (Variable)
              fun (Function that return a value of that particular logic)

4 typescript vs javascript 

5 Pre- requisites to run angular locally
 node.js & npm = dependency to run an angular project
  nvm = node version manager
  npm = node packaging manager
  Commands;
  how to check nvm version ? nvm version
  nvm install node_version 
  nvm list
  nvm use node_version
  how to check node version ? node -v / node --version
  how to check npm version ? npm -v / npm --v
  live reloading = ng build --watch (auto reloads changes in browser from a logic)

  Scaffolding for angular cli 
  npm install -g @angular/cli
  https://www.techladder.in/article/angular-cli-cheat-sheet
  ng v (to check cli version)
  ng generate component <component name>
  ng g c <component name>
  ng g d <directive-name>  to run animation icons 
  ng g s <service-name> shares data between components e.g car engine ignite with key
  ng g cl <class name>
  ng g i <interface name> e.g contract- its mentioned inside a class
  ng g p <pipe name>  (FOr Formatting text e.g date)
  ng g e <enum name>
  ng g m <module name>
  ng g guard <guard name> guard edit e.g can activate/deactive


  Array -> contineous allocation of elements
  var vegies = ["tomato", "carrot", "Brinjal"]
tomato =  vegies[0]
carrot =  vegies[1] 
Brinjal = vegies[2]
vegies.length // 3

import & export
service to share the data between components e.g car engine ignited with key
class it is a blueprint of structure how your object will look like
interface = its mentioned inside a class