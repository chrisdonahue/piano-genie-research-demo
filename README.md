# Piano Genie Demo

This model is the user interface and inference component of [Piano Genie](https://github.com/tensorflow/magenta/tree/master/magenta/models/piano_genie). Piano Genie allows you to control an 88-key piano via an intelligent 8-button interface.

This is the old demo with all the models from the research paper. Go [here](http://piano-genie.glitch.me) for a shiny demo featuring only our best model. Piano Genie code is available through [Magenta JS](https://github.com/tensorflow/magenta-js/tree/master/music).

## Demo

To view a hosted version of the demo, go to https://chrisdonahue.github.io/piano-genie-research-demo

## Building

To build, execute `yarn build` in the project directory. Then, type `yarn serve` to start a local server for the web demo.

## Testing

To test the models, first [download the test models bundled as JSON files](https://storage.googleapis.com/magentadata/js/checkpoints/piano_genie/testdata.zip). Extract the models into `piano-genie-js/testdata` and type `yarn test`.
