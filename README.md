先运行
```bash
docker-compose up -d
```

等完全启动后运行

```bash
docker-compose exec devtool-api npx ts-node dist/scripts/seed.js
```

[点此打开](http://localhost:54321)
