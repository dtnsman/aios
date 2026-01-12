# aios
ai os

written by ai

20k lines code

a big project written by T100 ai coder

[live demo](http://web3.dtns.top/os-i3.html)  

## usage:

### easily add url app

```javascript
AppManager.registerApp({
    id: 'web3OS',
    name: 'Web3 OS',
    icon: 'fas fa-globe',
    description: 'Web3 os website',
    color: '#8b5cf6',
    windowConfig: {
        width: 1200,
        height: 800
    },
    onLaunch: () => {
        const container = document.createElement('div');
        container.className = 'h-full';
        
        const iframe = document.createElement('iframe');
        iframe.src = 'http://web3.dtns.top/os.html?ib3hub=svrdev';
        iframe.className = 'w-full h-full border-0';
        iframe.allowFullscreen = true;
        
        container.appendChild(iframe);
        return container;
    }
});
```
