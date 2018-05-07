This work is licensed under Proprietary License。

本项目用私有授权协议。

start appifi in standalone mode:

node_modules/.bin/nodemon --ignore tmptest src/app.js --standalone --fruitmix-only --alice

--standalone start appifi in standalone mode
--fruitmix-only only start fruitmix, no boot; phy-drives api is not available in this mode
--alice fake first user as alice (phicommUserId: alice, password: alice)

