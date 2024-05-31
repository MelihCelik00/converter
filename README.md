# Converter

first change all input names to your geojson name i.e. if it's name.geojson convert all input.geojson's in Dockerfile and entrypoint.sh to name.geojson, name.mbtiles, and etc.

### to run

`docker build -t converter .`
`docker run converter`