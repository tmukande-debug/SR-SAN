

You can download the datasets which used in our paper from the following links. Then put them in the folder `datasets/`:

- YOOCHOOSE: <http://2015.recsyschallenge.com/challenge.html>

- DIGINETICA: <http://cikm2016.cs.iupui.edu/cikm-cup> or <https://competitions.codalab.org/competitions/11161>

After you download the YOOCHOOSE dataset, add headline with `session_id,timestamp,item_id,category` in the yoochoose-clicks.dat. 

## Usage

Run the file  `datasets/preprocess.py` to preprocess the data before train the model.

For example: `cd datasets; python preprocess.py --dataset=yoochoose`


## Requirements

- Python 3
- PyTorch 1.2
