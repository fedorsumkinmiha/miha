# miha
miha
{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.7",
    "configurations": [
        {
            "name": "Debug Jest Tests on Nix",
            "type": "node",
            "request": "launch",
            "runtimeArgs": [
              "--inspect-brk",
              "${workspaceRoot}/node_modules/.bin/jest",
              "--runInBand"
            ],
            "console": "integratedTerminal",
            "internalConsoleOptions": "neverOpen",
            "port": 1242
          }        
    ])
}
