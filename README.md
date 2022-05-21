# Intent Recognition with BERT

We build a model to recognise intents from a given query and output the scecific response

We used BERT as our pretrained model. To learn more about BERT click here https://arxiv.org/abs/1810.04805

We used a dataset having seven intents for our purpose

* SearchCreativeWork (e.g. Find me the I, Robot television show),
* GetWeather (e.g. Is it windy in Boston, MA right now?),
* BookRestaurant (e.g. I want to book a highly rated restaurant for me and my boyfriend tomorrow night),
* PlayMusic (e.g. Play the last track from Beyoncé off Spotify),
* AddToPlaylist (e.g. Add Diamonds to my roadtrip playlist)
* RateBook (e.g. Give 6 stars to Of Mice and Men)
* SearchScreeningEvent (e.g. Check the showtimes for Wonder Woman in Paris)

You can find the Dataset here https://github.com/sonos/nlu-benchmark/tree/master/2017-06-custom-intent-engines

The notebook will take you through the process of training the model