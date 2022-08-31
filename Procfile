web: node . --server && npm start
worker: npx pm2 start npm --node-args="--optimize_for_size --max_old_space_size=460" -- run db && npx pm2 logs
worker: npm i -g pm2 && pm2 index.js && pm2 save && pm2 logs
