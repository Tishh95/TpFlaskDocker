# TpFlaskDocker


Les commandes pour start 

docker build ./ -t pwv:v1

docker run -v $(pwd):/app -p 5000:5000 pwv:v1
