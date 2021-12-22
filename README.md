# Dog

Example app used to test docker and kubernetes services.
It's a simple go app that runs on port 4100 and renders dog image.

## Usage

    ./dog

## Docker usage

    docker build . -t andrzejtrzaska/dog
    docker run -p 4100:4100 andrzejtrzaska/dog
    curl -v http://localhost:4100

## License

MIT
