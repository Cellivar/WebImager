# Symbol / Zebra / Motorola model number information

Over the years Symbol has made many different imagers for many different use cases. The model number of the device gives a general hint towards its capabilities if you know what the codes mean, so when looking around for used units you can stick to ones that will do what you need.

## Model number breakdown

Symbol imagers have a full model number on the device that will look like

`DS9808-SR00007C1WR`

Zebra doesn't release official terminology for how this number breaks down. These are the terms I've seen.

| Name                   | Example            | Meaning                                                                                                                                                                                              |
| ---------------------- | ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Series                 | DS9800             | Official term. General hardware series, the same series will have similar physical bodies with different internals. The format is LLNN00, where LL is the scanner engine and NN is the Series Number |
| Series Submodel        | DS8178 and DS8108  | The last two digits of the series. Describes physical differences, such as the Corded DS8108 and Cordless DS8178.                                                                                    |
| Scanner Engine         | LS, LI, DS, MT, MC | How the imager does the scanning. See table below.                                                                                                                                                   |
| Model Feature          | -SR, -LR, -DL, -R  | The first two characters after the dash. Usually describe the scanner's internal configuration and the features that supports. See table below.                                                      |
| Hardware Configuration | 00007C1WR          | The rest of the model string, describes the internal board configuration for the imager.                                                                                                             |

So the `DS9808-SR00007C1WR` breaks down as:

* `DS9800` series
* `DS9808` submodel
* `DS` scanner engine
* `-SR` model feature
* `00007C1WR` hardware configuration


