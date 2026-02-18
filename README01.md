# 실행법

* pnpm install
* pnpm run dev
* pnpm build
* pm2 start ecosystem.config.cjs --name "my-sveltekit-app01"
* pm2 list
* pm2 stop 0
* pm2 delete 0
* pm2 restart 0

# 서버 재시작 시에도 실행
* pm2 save
* pm2 startup