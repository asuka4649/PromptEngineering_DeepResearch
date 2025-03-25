# Open Deep Research on Windows Powershell (without running Docker)

This project is based on dzhng's deep-search repository (https://github.com/dzhng/deep-research) project but in a much simpler way. 
And this was achievable purely with prompt engineering, command lining, and slight code modification.

# Implementation Steps
1. Create a project folder in your system
2. Open your Powershell and make sure node.js and git are installed
3. Connect Powershell to the project file (see "code" in deep-search page) and download the project package
     cd C:\path\to\your\desired\directory
     git clone https://github.com/username/repository.git
4. Install necessary files in the project folder
     npm install
5. In the repository, change .env.example to .env.local and copy-paste OpenAI and Firecrawl's APIs.
6. Change model name from o3-mini to gpt-4o in provider.ts
7. Comment out "reasoning" line in provider.ts file in src folder
8. Run the program via Powershell
     npm start
9. Ask anything
   
## License

MIT License - feel free to use and modify as needed.
