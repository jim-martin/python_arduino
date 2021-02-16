# python_arduino

To use these notebooks: 

1. setup the conda environment.

```
git clone https://github.com/jim-martin/python_arduino.git
cd python_arduino
conda env create -f environment.yml
conda activate pyserial
jupyter notebook
```

2. Open `signal_graph.ipynb` 
3. Update `port` to match your teensyduino port number (Teensyduino Tools -> Port)
4. Run the cell (shift+enter).
5. exports land in `python_arduiono/captures`
