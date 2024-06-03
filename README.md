# AngularTourOfHeroes

Angular tour of heroes tutorial without app modules

## Development server

Run `ng s` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng g c component-name` to generate a new component. You can also use `ng g directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help`.

# $${\color{purple}TherAIpy}$$

A personal diary that can go from being the best you've ever had hype man to your unofficial therapist that's there for you no matter what.

## How to Run

1. Use this line to clone the repository to your local machine
```bash
git clone https://github.com/kauraraj/HackKU2024.git
```
2. Install it through the Installation Guide below.
3. Get an OpenAI API key and put it into where the open string is in ./server/index.js
4. Terminal 1:
```bash
cd ..
make servers
```
6. Terminal 2:
```bash
cd ..
make clients
```


## Installation

Use the Node Package Manager (npm) to install all dependencies.

```bash
cd client
cd ..
npm install express cors body-parser openai morgan dotenv axios --save
cd server
cd ..
npm install express cors body-parser openai morgan dotenv axios --save
```

## Usage

Type diary responses into the web application and then interact with the positive, kind, therapeutic, friendly AI bot. When you can't afford therapy, they're there to give you therAIpy.

## Contributing

[Do not allow contributing until after the end of HACKKU2024]
Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
