# docker-sigal 
docker with python3.6 and sigal (http://sigal.saimon.org/en/latest/index.html)
generates a static gallery from /src to /html

# usage
docker run --mount type=bind,source=INFOLDER,target=/src --mount type=bind,source=OUTFOLDER,target=/html hizlbuzz/sigal
