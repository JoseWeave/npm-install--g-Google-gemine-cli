☆(Install "Gemini CLI" globally w/ NPM): npm install -g @google/gemini-cli
☆(RUN:Gemini CLI with the gemini):        ?/docs/cli/cli-reference.ll           bash                                     gemini
☆(Run w/ NPX: NO PERM. Install):           <Tabs><TabItem_label="npx">
☆Using NPX (NO INSTALL REQ.):              <npx @google/gemini-cli>
☆Execute CLI, directly from main branch on GitHub. (Helpful for testing features still in dev.):                       bash                                     npx https://github.com/google-gemini/gemini-cli
</TabItem><TabItem label="Docker/Podman Sandbox">
☆Run the CLI:                             bash                                    ☆Run the PUBLISHED SANDBOX IMAGE for a specified CLI version:                    docker run --rm -it us-docker.pkg.dev/ gemini-code-dev/gemini-cli/               sandbox:0.42.0-                           nightly.20260428.g59b2dea0e
☆Instruct it to RUN INSIDE the SANDBOX CONTAINER:                                bash.                                     gemini--sandbox -y -p "your prompt here"
☆Run CLI (directly from the SOURCE CODE):</TabItem><TabItem label="From source">
☆ DEVELOPMENT MODE: Provides HOT RELOADING. Useful for ACTIVE DEVELOPMENT.                  bash.                                                                                       (From the ROOT of the REPOSITORY):                                                           npm run start
