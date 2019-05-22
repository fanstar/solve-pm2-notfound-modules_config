
Error: ENOENT: no such file or directory, open '/home/ubuntu/.pm2/module_conf.json'
    at Object.fs.openSync (fs.js:646:18)
    at Object.fs.readFileSync (fs.js:551:33)
    at Object.Configuration.getAllSync (/usr/lib/node_modules/pm2/lib/Configuration.js:295:26)
    at Object.Configuration.getSync (/usr/lib/node_modules/pm2/lib/Configuration.js:266:30)
    at new API (/usr/lib/node_modules/pm2/lib/API.js:117:36)
    at Object.<anonymous> (/usr/lib/node_modules/pm2/bin/pm2:28:11)
    at Module._compile (module.js:653:30)
    at Object.Module._extensions..js (module.js:664:10)
    at Module.load (module.js:566:32)
    at tryModuleLoad (module.js:506:12)
fs.js:646
  return binding.open(pathModule._makeLong(path), stringToFlags(flags), mode);
  
  
  sudo pm2 delete all
  
  reinstall again
  sudo pm2 install pm2 -g
