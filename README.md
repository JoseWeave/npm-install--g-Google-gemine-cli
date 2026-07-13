☆(Install "Gemini CLI" globally w/ NPM):   #npm install -g @google/gemini-cli
☆(RUN:Gemini CLI with the gemini):          #?/docs/cli/cli-reference.ll               bash                                      gemini
☆(Run w/ NPX: NO PERM. Install):           #<Tabs><TabItem_label="npx">
☆Using NPX (NO INSTALL REQ.):              #npx @google/gemini-cli
☆Execute CLI: Directly from main branch on GITHUB:(For TESTING FEATURES still in DEVELOPMENT:                          bash                                      #npx https://github.com/google/google-gemini/gemini-cli.                        
(For SECURITY & ISOLATION):                *GEMINI CLI can be run INSIDE of a CONTAINER. (This is the DEFAULT way that the CLI executes TOOLS that may have "side effects"). You can run the PUBLISHED SANDBOX IMAGE Directly. (Useful for ENVIRONMENTS, where you only have DOCKER)
#RUN the CLI:                              ☆Run the PUBLISHED SANDBOX IMAGE for a specified CLI version:                     #docker run --rm -it us-docker.pkg.dev/    gemini-code-dev/gemini-cli/               sandbox:0.42.0-                           nightly.20260428.g59b2dea0e
☆Instruct it to RUN INSIDE the SANDBOX    CONTAINER:                                bash                                 #gemini--sandbox -y -p "your prompt here"
☆Run CLI (directly from the SOURCE CODE):   </TabItem><TabItem label="From source">
☆DEVELOPMENT MODE: Provides HOT RELOADING. Useful for ACTIVE DEVELOPMENT: (From the ROOT of the REPOSITORY):         #npm run start
☆PRODUCTION MODE (REACT Optimizations):    ● This method RUNS THE CLI (w/) REACT, while PRODUCTION MODE is ENABLED. (For TESTING PERFORMANCE (w/o DEVELOPMENT OVERHEAD):                                 bash                                     #npm run start:prod
☆PRODUCTION-LIKE MODE (Linked Package):    ● This method STIMULATES a GLOBAL INSTALLATION, by LINKING your LOCAL PACKAGE. (Useful for TESTING a LOCAL BUILD in a PRODUCTION WORKFLOW.      ☆LINK your LOCAL PACKAGE to your GLOBAL NODE_MODULES:                              #npm link package/cli
☆NOW: You can run your local version using GEMINI COMMAND:                     #gemini                                    '''                                       </TabItem>                                </Tabs>
