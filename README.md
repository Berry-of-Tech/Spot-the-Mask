# Spot-the-Mask

<div align="center">
    <img src = "https://github.com/Berry-of-Tech/Spot-the-Mask/blob/main/spot%20the%20mask%20(2).jpg" 
     height = "500"
     width = "1000">
</div>

## <span style='color:green'> Description </span>


In the midst of concerns over COVID-19 transmission, combining AI solutions with increased surveillance can improve monitoring and reduce human effort needed to limit the disease's spread.
 

##  😷<span style='color:green'> The solution </span> 🧠
Our solution is based on the architechture of the well known model <a href="https://pytorch.org/hub/pytorch_vision_densenet/">Densnet</a> and uses the technique of transfer learning to get some learned features form others tasks and use them in this contest to help our custom model to make accurate predictions.

<div align="center">
    <img src = "https://pytorch.org/assets/images/densenet1.png" 
        height = "400"
        width = "800">
</div>

The main framework used to implement the model is <a href="https://pytorch.org/get-started/locally/">Pytorch</a>.

With this model and with all the others techniques applied, we have been able to get the following results:

<div align='center'>

|set        | loss (log_loss)      | accuracy  |
|-----------|----------------------|-----------|
|training   |0.001918              | 99.242  % |
|test       |0.001099342           | 98.141 %  |

</div>

```
MIT License

<<<<<<< HEAD
Copyright (c) 2020 TheCIA.
=======
## Final Leaderboard
>>>>>>> 23c9dbce4e880024d23d8a776913ea4b51727263

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
