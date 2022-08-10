# LM13700-spice-model
A more useful spice model for simulating the LM13700 chip as a dual unit in SPICE.

With this additional spice model for dual use, it is easier to simulate the LM13700. 
## Usage in KiCad

- Download LM13700 files and place in KiCad project folder
- Open Schematic editor
- Rename LM13700, for example "U1" has to become to 'XU1'
- Double click on LM13700 symbol for opening 'symbol properties'
- Click on 'Spice Model'
- Go to 'Model' tab
- Select the LM13700-DUAL.LIB
- Model: LM13700-DUAL.LIB
- Type: Subcircuit
- No alternative node sequence is needed!

That's all, click on ok and start simulating.
