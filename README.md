\*\* Steps that i have taken while setup:

    1. initially i used the cmd of npm create-react-app /folderName
    2. then i went to the bootstrap site and chosen the react starter page
    3. copied the cmd in which it has npm install react-bootstrap bootstrap. which will install react-bootstrap and bootstrap in the node modules.
    4. then i modified the app.js file and eradicated the existing boilerplate code.
    5. Installed the bootstrap-icon through this command => npm i bootstrap-icons
    6. then analyzed the different between the raw html + bootstrap code nand the react as well. In which, the code is writtend in the format of component instead of raw code.
    7. Then i added custom theme setting in the bootstrap using sass in which i went into node_modules/bootstrap/sass/variable.scss and then i found the primary variable and copied it and then i pasted in main.scss which i created inside the sass folder by importing 👇

            #code inside main.scss:

                    $primary : #ff6347;

                    @import '../node_modules/bootstrap/scss/bootstrap';
        
    8. By changing this we can change the default theme into custom theme.
    
