
        ☆Install Gemini CLI☆:
(1)Install "Gemini CLI" globally:
●[npm install -g @google/gemini-cli]

(2)Open: "cloudshell" OR "Cloud Workstation"

(3)Open:(Terminal)/(Command Prompt).

(4)Open:"Gemini Code Assist",& type in:
  <Tabs><TabItem_label="npm">
                                **(ANACONDA=(NEW ENVIRONMENT)**

(5)[Create:(NEW ENVIRONMENT):
1[conda create -y -n gemini_env-c conda-]
2[forget nodejs                         ]
3[conda activate gemini_env             ]
4[                                      ] 5[<br>                                  ]

         ☆Install Gemini CLI☆
  
(6)Open: "cloudshell" OR "Cloud Workstation"
  
(7)Open:(Terminal)/(Command Prompt),& then:      
 (#)=([?/docs/cli/cli-reference.ll])            
   
 [  bash            ]                              
 [                  ]
 [  gemini          ]

(8)[Run w/ NPX: (No Perm.Install)]:            
(#)= <Tabs><TabItem_label="npx">

(9)Using NPX (NO INSTALL REQ.):      
(#)= npx @google/gemini-cli

 ☆Execute CLI,Directly from main branch☆ (For TESTING FEATURES still IN DEVELOPMENT):  

(10):(#)= [npx instll -g@google/gemini-cli]

(11)[https://github.com/google/google-gemini/gemini-cli.                        

      ☆(For SECURITY & ISOLATION)☆:                 **GEMINI CLI can be run INSIDE ofa CONTAINER. (This is the DEFAULT way that the,"CLI", executes TOOLS that MAY have "SIDE EFFECTS"). 

             ☆RUN THE CLI☆
  ● You can run the PUBLISHED SANDBOX IMAGE: (Useful for ENVIRONMENTS, where u ONLY have: DOCKER)                                                 
   
(12)Run the PUBLISHED SANDBOX IMAGE for a specified CLI version:
          ☆[(LINE #'s):(1-5)]☆                    
(1)docker run --rm -it us-docker.pkg.dev/            
(2)gemini-code-dev/gemini-cli/                   
(3)sandbox:0.42.0- 
(4)                                              
(5)nightly.20260428.g59b2dea0e

(13) Instruct it to Run INSIDE of the:       
         ☆SANDBOX CONTAINER☆                             bash                                 

gemini--sandbox -y -p "your prompt here"

(14)Run CLI: (directly from the SOURCE CODE):   (#)= </TabItem><TabItem label="From source">

**DEVELOPMENT MODE**: 
 ● Provides HOT RELOADING;   
 ● Useful for ACTIVE DEVELOPMENT)

(15)[From the ROOT of the REPOSITORY]:        
(#)= npm run start

  ☆PRODUCTION MODE (REACT Optimizations)☆   ●RUNS THE CLI (w/) REACT, while; 
●PRODUCTION MODE is ENABLED. 

(16)For TESTING PERFORMANCE, (w/o) any: "DEVELOPMENT OVERHEAD":                                  
  bash                                          
 
 [npm run start:prod]

☆PRODUCTION-LIKE MODE (Linked Package):    ●   
           ☆This method:
●STIMULATES a GLOBAL INSTALLATION, by: ●LINKING your LOCAL PACKAGE.
●Useful for TESTING a (LOCAL BUILD), in a: PRODUCTION WORKFLOW    

 ☆LINK your LOCAL PACKAGE to your GLOBAL NODE_MODULES:                              #npm link package/cli

●NOW: You can run your local version using GEMINI COMMAND:                        
gemini                                                         '''                                                </TabItem>                                  </Tabs>

☆RELEASES:GEMINI CLI has... 
☆3 "RELEASE CHANNELS":     
    ●STABLE(Recommended;Default installation)  
    ●PREVIEW (&)            
    ●NIGHTLY
  
**(NOTE): ASSUME that there ARE,"PENDING- (VIOLATIONS/ISSUES)".

☆Help to TEST THE LATEST CHANGES by:
  ●Installing (w/) NIGHTLY Tag:                
<TABS>                                     bash                                    
npm #install-g @google/gemini-cli@nightly   </TabItem>                                  </Tabs>                                   <TabItem label="nightly">
