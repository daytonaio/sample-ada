This repository contains a README file sample for Daytona Samples and the MIT License.

It can be used as a template to create sample repositories that can be added into [Daytona](https://github.com/daytonaio/daytona).

Once you finish your sample and it gets merged, you can open a PR in the Daytona repo and submit the sample into the [index file](https://github.com/daytonaio/daytona/blob/main/hack/samples/index.json).

# Sample Ada

This is an example Ada Programming Language project used in Daytona.

---

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  
2. **Create the Workspace**:  
   ```bash  
   daytona create https://github.com/daytonaio/sample-ada
   ```  
3. **Start the Application**:  

Open the terminal and run:

   ```bash  
   gprbuild -P hello_world.gpr src/hello_world.adb -cargs:ada -gnatef
   ./obj/hello_world
   ```  

Or just press the Run Code button (Ada: Build and run last used main) found in the top right of the editor panel.

---

## ✨ Features  

Standardized development environment with devcontainers

Console application
