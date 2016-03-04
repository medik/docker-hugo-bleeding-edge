# Hugo-docker

## Build 
If needed, modify `run.sh`. Then run the command in the same directory as
Dockerfile `docker build -t hugo .`.

## Usage
Paste this following command and let `$DIR` be the path where your hugo directory is living.
`docker run -d -p 80:1313 -v $DIR:/hugo hugo`

## Contribution 
Make a pull request with your contribution. All contributions are welcome.
