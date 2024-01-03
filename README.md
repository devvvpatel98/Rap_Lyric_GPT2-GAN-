Make sure to run:

!pip install datasets
!pip install transformers
!pip install accelerate -U

At the very top of the colab notebook.

To replicate the experiment, start about halfway down in the code block that says:

from google.colab import drive
drive.mount('/content/drive')

(Above the code block that has):

import matplotlib.pyplot as plt
x = [1,1,1]
plt.plot(x)
plt.savefig('/content/drive/MyDrive/test.png')

Then you can run everything below it and this should be good!