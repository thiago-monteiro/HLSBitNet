# Exporting BitNet to Binary

To export BitNet you can use the modified export.py file based on llama2.c. Ideally the BitNet would've been trained from scratch to be ternary (otherwise it will generate nonsense when it's quantized so heavily) but as a test you can quantize Andrej Karpathy's tinyStories LLaMA using the following command: `python export_bitnet.py weights.bin --version 2 --checkpoint stories110M.pt`
