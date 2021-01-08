# wg-tunel

docker-composer for https://github.com/whyvra/tunnel
```sh
git clone https://github.com/pomazanbohdan/wg-tunel.git
cd wg-tunel
docker-composer up -d
```

If you use Traefik:
- comment ports 
- uncomment label and network
- change domain and traefik network for you setting