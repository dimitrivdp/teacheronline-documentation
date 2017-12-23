

ember install 

const userAgent = this.get('userAgent');

userAgent.get('browser.isChrome'); // Boolean
userAgent.get('engine.isWebKit'); // Boolean
userAgent.get('os.info'); // => { name: 'Ubuntu', version: '11.10' }
userAgent.getDevice(); // => { model: 'iPhone 7', type: 'mobile', vendor: 'Apple'}