# Spot-the-Mask

<div align="center">
    <img src = "[https://pbs.twimg.com/media/EVyYt-IU8AALA3x.jpg](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.myadorna.com%2Fproducts%2Fpack-of-5-anti-pollution-virus-protection-face-masks&psig=AOvVaw1WCVh1kAiPBlBQ7EAKbfq9&ust=1708601496140000&source=images&cd=vfe&opi=89978449&ved=0CBMQjRxqFwoTCOCwyNmqvIQDFQAAAAAdAAAAABAF)" 
     height = "500"
     width = "1000">
</div>

## 🗒<span style='color:green'> Description </span>


In a time of concerns about slowing the transmission of COVID-19, increased surveillance combined with AI solutions can improve monitoring and reduce the human effort needed to limit the spread of this disease.

Since the anouncement of a lockdown, generalized in many counntries over the world due to the spread of COVID-19, Zindi community has started a new type of challenges called <span style='color:red'>#ZINDIWEEKENDZ </span>. It is a set of competitions based on data science in order to permit to all the #zindians the development of AI based solutions in order to use their skills for giving their community some technical means and  viable solutions to their community in this biological war.
A challenge is taking place every weekend from April to May 2020.

This hackathon was about predicting whether a person in an image is wearing a face mask or not. It was hosted by [Zindi](https://zindi.africa/hackathons/spot-the-mask-challenge/) and lasted for 3 days (from Thursday 17 April to Sunday 19).  

##  😷<span style='color:green'> The solution </span> 🧠
Our solution is based on the architechture of the well known model <a href="https://pytorch.org/hub/pytorch_vision_densenet/">Densnet</a> and uses the technique of transfer learning to get some learned features form others tasks and use them in this contest to help our custom model to make accurate predictions.

<div align="center">
    <img src = "https://pytorch.org/assets/images/densenet1.png" 
        height = "400"
        width = "800">
</div>

The main framework used to implement the model is <a href="https://pytorch.org/get-started/locally/">Pytorch</a>. Some of us also used [Tensorflow 2.0](https://www.tensorflow.org/), [keras](https://keras.io/) and [scikit-learn](https://scikit-learn.org/stable/) when experimenting.

With this model and with all the others techniques applied, we have been able to get the following results:

<div align='center'>

|set        | loss (log_loss)      | accuracy  |
|-----------|----------------------|-----------|
|training   |0.001918              | 99.242  % |
|test       |0.001099342           | 98.141 %  |

</div>
