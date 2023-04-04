## dalle-cli
This script uses OpenAI's API to generate an image based on the user's input prompt. The generated image will be opened in the user's default web browser.

## Prerequisites
You need to have the following installed on your system:

* Node.js
* npm
* You also need an API key from OpenAI.

## Installation
Clone the repository or download the code.

Install the required dependencies by running the following command in the project folder:
```
npm install
```

Set up an environment variable with your OpenAI API key:
```
export OPENAI_KEY=<your-api-key>
```

Link the binary to your local bin folder:
```
npm link
```

## Usage
Run the script by entering the following command in your terminal:

```
dalle <prompt> [--medium | --large]
```
`<prompt>`: The text prompt that describes the image you want to generate.

`--medium`: (Optional) Generate a 512x512 image. If not specified, the default size is 256x256.

`--large`: (Optional) Generate a 1024x1024 image. If not specified, the default size is 256x256.

Example
```
dalle A beautiful sunset on a beach --medium
```
This command will generate a 512x512 image an open it in your default web browser.
