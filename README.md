# Biometric Systems website

## Local development

```bash
docker run --rm -it \  
-v $(pwd):/src \    
-p 1313:1313 \
klakegg/hugo:0.89.4-ext \
server
open http://localhost:1313/biometric-systems/
```
