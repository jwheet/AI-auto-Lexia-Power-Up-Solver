# AI-auto-Lexia-Power-Up-Solver

This repository contains an automated solver script designed to assist with Lexia PowerUp tasks. The script runs inside the browser using a user-script manager such as Tampermonkey and uses an external AI API to generate answers for the activities displayed on the Lexia platform.

This README provides installation instructions, API key setup, usage details, and an advanced overview of how the solver works internally.

---

## Features

- Automatically detects questions inside Lexia PowerUp
- Sends the detected content to an external AI model
- Inserts generated answers directly into the activity interface
- Supports user-provided API keys for full control and privacy
- Lightweight and easy to install

---

# Installation

## 1. Install a User-Script Manager

To run the solver, you must install a browser extension capable of executing user scripts. The recommended option is **Tampermonkey**.

### Supported Browsers
- Firefox
- Chrome / Brave / Edge / other Chromium-based browsers
- Opera (with userscript support)

Once installed, confirm that Tampermonkey is active in your browser's extensions list.

---

## 2. Install the Solver Script

After Tampermonkey is installed, open the script page below and click **Install**:

**Script Link:**  
https://greasyfork.org/en/scripts/558194-lexia-powerup-solver-pro

This will load the user script directly into Tampermonkey.

---

# API Key Setup

The script requires an API key to communicate with an AI model. Follow the steps below to obtain and configure the key.

## 1. Create an API Key
1. Visit **OpenRouter**: https://openrouter.ai
2. Log in or create an account.
3. Go to **Dashboard → API Keys**.
4. Click **Create Key**.
5. Copy the generated key.

Keep your key private. Do not share it publicly.

---

## 2. Insert the API Key into the Script

1. Open your browser.
2. Click the **Tampermonkey** icon.
3. Select **Dashboard**.
4. Find **Lexia PowerUp Solver Pro** in your script list.
5. Click **Edit**.
6. Locate the configuration section near the top of the script:

`const OPENROUTER_API_KEY = "YOUR_KEY_HERE";`

---



                                                                                                    
                                            ==                                                      
                                          =======                                                   
                                       ===========                                                  
                                         =============         *===                                 
                                     ================       %*+====+                                
                                       =============     %%#+%======                                
                                         ==========+++++  %%*==========                             
                                      =============++++    %%=========                              
                                       ===========+++++#####=========                               
                                         =========++++  ####============                            
                                       ==============++++###==========                              
                                       %============++++***=========                                
                                     +#%%+==========++*****============                             
                                      +**%#========+++=#***+=========                               
                                      ==*+#========+++=##***========                                
                               +== +++===+#%+======++==*****=======                                 
                               ===+++++===========+*====****=====+                                  
                             ====================+++=====##*=++++===                                
                            =========+++=========++========+++++=====                               
                              ====+===+==+====+==++=====+%%*++++======                              
                             =+=======+=+++==+===++======++++++======                               
                               ======+====*==*===++=====+++++++=======                              
                               +=========+*%*+==+++=====++++++======                                
                                 ========+*##*==+++=====++++++++++*                                 
                                  +==++==+=*#*==+++=====++++++==++++                                
                                    =====***#+==+++===++++++++++++                                  
                                      ===+#%*===++++=   +++++++++                                   
                                      ====+%*==+=+==      ++++                                      
                                      ====+ *==+=+==     +===                                       
                                       ====+*==+=+==     ====                                       
                                       ====+*==+=+=     ====                                        
                                       ==+==#==++==    =====                                        
                                       ==+==*==++==    ====                                         
                                        ==*=*===+==   =====                                         
                                        #***#======%%@====                                          
                                        %*%%###############                                         
                                         *=*#===+== ==+==                                           
                                          ==%===*==#==+==                                           
                                          *=%========++=                                            
                                          %+*==+=+==++==                                            
                                          %%%*+++%**####%                                           
                                           +*########*==                                            
                                           =**==+#==++=                                             
                                           =++==+*=====                                             
                                           =====++=====                                             
                                           =====++=====                                             
                                           ============                                             
                                           ======+=====                                             
                                           ======++====                                             
                                            ==+==++====                                             
                                            ==*==++===                                              
                                            == == ++==                                                                                                                                                                                                                                        
                              ____.       .__                   __   
                             |    |_  _  _|  |__   ____   _____/  |_ 
                             |    \ \/ \/ /  |  \_/ __ \_/ __ \   __\
                         /\__|    |\     /|   Y  \  ___/\  ___/|  |  
                         \________| \/\_/ |___|  /\___  >\___  >__|  
                                           \/     \/     \/      
                     
