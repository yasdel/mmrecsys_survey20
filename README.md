# Recommender System Leveraging Multimedia Content

A table of publications on multimedia recommender systems, in particular recommender systems that leverage multimedia content. This page will be ****periodically**** updated to include the most recent works. Please contact us if your work is not in the list.

The table serves as overview and extension of the works discussed in the following survey. Please consider citing it if you think it is useful.

```
@article{mmrecsys2020deldjoo,
  title={Recommender System Leveraging Multimedia Content},
  author={Yashar Deldjoo and Markus Schedl and Paolo Cremonesi and Gabriella Pasi},
  journal={ACM Computing Surveys},
  year={2020}
}
```

## Papers
### Audio

### Sounds
| Year  | Authors | Title       |Venue  | Target Item    | Paper        |Code |Data/Source|
|------|-------|-------|------|-----------|---------------|-------|-------|
|2015| Oramas et al.|**A Semantic Hybrid Approach for Sound Recommendation.**|WWW|![sound_track](https://user-images.githubusercontent.com/12104758/82208688-438a0f00-990c-11ea-8386-250e3d2a0269.png)|[Link](https://dl.acm.org/doi/10.1145/2740908.2742775)|--|[DBpedia](http://dbpedia.org/)<br>[WordNet](https://wordnet.princeton.edu/)<br>[FreeSound](http://linkeddata.org/)||
|2016| Ostuni et al. | **Sound and Music Recommendation with Knowledge Graphs.**|TIST|![sound_track](https://user-images.githubusercontent.com/12104758/82208688-438a0f00-990c-11ea-8386-250e3d2a0269.png)|[Link](https://dl.acm.org/doi/10.1145/2926718)|--|[Songfacts](http://songfacts.com/)<br>[Last.fm](http://last.fm/)<br>[FreeSound](http://linkeddata.org/)||
|2019| Smith et al. |**Towards a Hybrid RecommendationSystem for a Sound Library.**|IUI|![sound_track](https://user-images.githubusercontent.com/12104758/82208688-438a0f00-990c-11ea-8386-250e3d2a0269.png)|[Link](http://ceur-ws.org/Vol-2327/IUI19WS-MILC-5.pdf)||[EarSketch](https://earsketch.gatech.edu/earsketch2/)|--||


### Music/Artist:
| Year  | Authors | Title      |Venue |Target Item | Link        |Code | Data|
|------|-------|-------|----------|-----------|---------------|-------|-------|
|2008|Yoshii et al.|**An Efficient Hybrid Music Recommender System Using an Incrementally Trainable Probabilistic Generative Model.**|IEEE Tr. ASLP|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://ieeexplore.ieee.org/document/4432655)|--|[DS_name](https://earsketch.gatech.edu/earsketch2/)||
|2009|Shao et al.|**Music recommendation based on acoustic features and user access patterns.**|ACM Tr. ASLP|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://ieeexplore.ieee.org/document/5230332)|--|[New Wisdom](www.newwisdom) (NA)||
|2010|Bu et al.|**Music recommendation by unified hypergraph: combining social media information and music content.**|ACM MM|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://dl.acm.org/doi/10.1145/1873951.1874005)|--|[Last.fm](http://last.fm/)||
|2013|Van den Oord et al.|**Deep Content-based Music Recommendation.**|NIPS|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://papers.nips.cc/paper/5004-deep-content-based-music-recommendation)|--|[Million Song Dataset (MSD)](http://millionsongdataset.com/)||
|2014|Shah et al.|**ADVISOR: Personalized Video Soundtrack Recommendation by Late Fusion with Heuristic Rankings.**|ACM MM|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://dl.acm.org/doi/10.1145/2647868.2654919)|--|[Last.fm](http://last.fm/)<br>[FourSquare](www.foursquare.com) (NA)<br>[GeoVid app](http://www.geovid.org)<br>||
|2013|Kaminskas et al.|**Location-aware music recommendation using auto-taggingand hybrid matching.**|RecSys|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://doi.org/10.1145/2507157.2507180)|--||
|2015|Liang et al.|**Content-Aware Collaborative Music Recommendation Using Pre-trained Neural Networks.**|ISMIR|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](http://ismir2015.uma.es/articles/290_Paper.pdf)|[Link1](https://github.com/dawenl/deep_tagging)<br>[Link2](https://github.com/dawenl/content_wmf)|[Million Song Dataset (MSD)](http://millionsongdataset.com/)||
|2014|Wang et al.|**Improving Content-based and Hybrid Music Recommendation Using Deep Learning.**|ACM MM|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://doi.org/10.1145/2647868.2654940)||[Echo Nest Taste](http://millionsongdataset.com/)<br>[7digital](http://7digital.com)||
|2017|Oramas et al.|**A Deep Multimodal Approach for Cold-start Music Recommendation..**|DLRS|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://doi.org/10.1145/2507157.2507180)|[Link](https://github.com/sergiooramas/tartarus)|[Million Song Dataset (MSD)](http://millionsongdataset.com/)||
|2011|McFee et al.|**The Natural Language of Playlists.**|ISMIR|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://ismir2011.ismir.net/papers/PS4-11.pdf)||[MSD](http://millionsongdataset.com/)<br>[Echo Nest](http://developer.echonest.com/)<br>[Last.fm](http://last.fm/)<br>[Art of the Mix(AotM)](http://www.artofthemix.org/)||
|2019|Vall et al.|**Feature-Combination Hybrid Recommender Systems for Automated Music Playlist Continuation.**|UMUAI|![music_artist](https://user-images.githubusercontent.com/12104758/82208151-52bc8d00-990b-11ea-897d-d64879eba58b.png)|[Link](https://link.springer.com/article/10.1007/s11257-018-9215-8)|[Link](https://github.com/andreuvall/HybridPlaylistContinuation)|[DS_name](TBA)||

### Image-based Recommendation
### target: product (leveraging visual content of the associated images) 
| Year  | Authors | Title       |Venue | Target Item | Link      |Code | Data|
|------|-------|-------|----------|-----------|---------------|-------|-------|
|2006|Boutemedjet et al.|**A generative graphical model for collaborative filtering of visual content.**|ICDM|![interface(1)](https://user-images.githubusercontent.com/12104758/82257995-4e1ec580-9959-11ea-97ce-1fe1968e4af6.png)|[Link](https://link.springer.com/chapter/10.1007/11790853_32)|--|[WashingtonUni. ImageDB](http://www.cs.washington.edu/research/imagedatabase/)||
|2008|Boutemedjet et al.|**A graphical model for context-aware visual content recommendation.**|IEEE Tr. MM|![interface(1)](https://user-images.githubusercontent.com/12104758/82257995-4e1ec580-9959-11ea-97ce-1fe1968e4af6.png)|[Link](https://ieeexplore.ieee.org/document/4407505)|--|[WashingtonUni. ImageDB](http://www.cs.washington.edu/research/imagedatabase/)||
|2014|Wu et al.|**Learning to personalize trending image search suggestion.**|SIGIR|![bacteria](https://user-images.githubusercontent.com/12104758/82293732-4db01a00-99ad-11ea-8d94-4a3e27fd31d4.png)|[Link](https://doi.org/10.1145/2600428.2609569)||[Search Logs](NA)||
|2010|Cui et al.|**Multiple feature fusion for social media applications.**|SIGMOD|![social-media](https://user-images.githubusercontent.com/12104758/82432121-def7bd00-9a8f-11ea-84c0-6011c7bdfe53.png)|[Link](https://dl.acm.org/doi/pdf/10.1145/1807167.1807216)| |[FlickerAPI](http://www.flickr.com/services/api/)||
|2018|Niu et al.|**Neural Personalized Ranking for Image Recommendation.**|WSDM|![social-media](https://user-images.githubusercontent.com/12104758/82432121-def7bd00-9a8f-11ea-84c0-6011c7bdfe53.png)|[Link](https://doi.org/10.1145/3159652.3159728)||[Flickr YFCC100M](https://arxiv.org/abs/1503.01817)||
|2015|Geng et al.|**Learning Image and User Features for Recommendation in Social Networks.**|ICCV|![pinterest](https://user-images.githubusercontent.com/12104758/82451453-4fadd200-9aae-11ea-919f-08b6168e6bd7.png)|[Link](https://doi.org/10.1109/ICCV.2015.486)|[Link](https://github.com/snownus/pinterest_crawler)|[Data (Pinterest)](https://drive.google.com/file/d/0B0l8Lmmrs5A_REZXanM3dTN4Y28/view)||
|2010|Albanese et al.|**A multimedia recommender integrating object features and user behavior.**|MTAP|![design](https://user-images.githubusercontent.com/12104758/82451769-b7641d00-9aae-11ea-8c7a-199b718119c3.png)|[Link](https://link.springer.com/article/10.1007/s11042-010-0480-8)|--|Uffizi Gallery (NA)||
|2013|Albanese et al.|**A multimedia recommender system**|TOIT|![design](https://user-images.githubusercontent.com/12104758/82451769-b7641d00-9aae-11ea-8c7a-199b718119c3.png)|[Link](https://dl.acm.org/doi/10.1145/2532640)|--|Uffizi Gallery (NA) <br> [ImdbAPI](http://imdbapi.org/)||
|2013|Bartolini et al.|**Recommending multimedia objects in cultural heritage applications.**|ICIP|![design](https://user-images.githubusercontent.com/12104758/82451769-b7641d00-9aae-11ea-8c7a-199b718119c3.png)|[Link](https://doi.org/10.1007/978-3-642-41190-8_28)|--|Manual-buit repo about Paestum (NA)||
|2011|Bourke et al.|**The social camera: a case-study in contextual image recommendation.**|IUI|![arrow](https://user-images.githubusercontent.com/12104758/82461302-8d185c80-9aba-11ea-8f5a-b1dee1bea1b0.png)|[Link](https://doi.org/10.1145/1943403.1943408)|--|NA||
|2017|Rawat et al.|**ClickSmart: A Context-Aware Viewpoint Recommendation System for Mobile Photography.**|IEEE Tr. CSVT|![arrow](https://user-images.githubusercontent.com/12104758/82461302-8d185c80-9aba-11ea-8f5a-b1dee1bea1b0.png)|[Link](https://ieeexplore.ieee.org/abstract/document/7456258)|--|[FlickerAPI](http://www.flickr.com/services/api/)||
|2016|Nguyen et al.|**NowAndThen: a social network-based photo recommendation tool supporting reminiscence.**|MUM|![arrow](https://user-images.githubusercontent.com/12104758/82461302-8d185c80-9aba-11ea-8f5a-b1dee1bea1b0.png)|[Link](https://dl.acm.org/doi/10.1145/3012709.3012738)|--|[Oxford Building DS](http://www.robots.ox.ac.uk/~vgg/data/oxbuildings/)||
|2018|Wen et al.|**Visual Background Recommendation for Dance Performances Using Deep Matrix Factorization.**|TOMCCAP|![birthday-and-party](https://user-images.githubusercontent.com/12104758/82476535-898ed080-9ace-11ea-8df3-ab00503cc197.png)|[Link](https://doi.org/10.1145/3152463)|--|Pinterest||
|2017|Peska et al.|**Towards Recommender Systems for Police Photo Lineup.**|DLRS*|![people](https://user-images.githubusercontent.com/12104758/82477123-48e38700-9acf-11ea-9346-cf98c1508abf.png)|[Link](https://dl.acm.org/doi/10.1145/3125486.3125490)|[Link](http://github.com/lpeska/lineups)|[Data](https://tinyurl.com/yat3rtr2)||

### target: product (leveraging visual content of the associated images) 
| Year  | Title       |Target Item  | Venue    | Link        |Code | Data|
|------|-------|----------|-----------|---------------|-------|-------|
|2015|**Image-based recommendations on styles and substitutes.**|SIGIR|Fashion|[Link]()||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2016|**Modeling the visual evolution of fashion trends with one-class collaborative filtering.**|WWW|Fashion|[Link]()||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2016|**Ups and downs: Modeling the visual evolution of fashion trends with one-class collaborative filtering.**|WWW|Fashion|[Link]()||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2018|**Aesthetic-based clothing recommendation.**|WWW|Fashion|[Link]()||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2018|**Personalized clothing recommendation combining user social circle and fashion style consistency.**|MTAP|Fashion|[Link]()||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2016|**UbiShop: Commercial item recommendation using visual part-based object representation.**|MTAP|Fashion|[Link]()||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2016|**iGlasses: A Novel Recommendation System for Best-fit Glasses.**|SIGIR|Fashion|[Link]()||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2014|**Effect of facial makeup style recommendation on visual sensibility.**|MTAP|Fashion|[Link]()||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2017|**Rule-based facial makeup recommendation system.**|FC 2017|Fashion|[Link](https://doi.org/10.1109/FG.2017.47)||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2017|**Examples-Rules Guided Deep Neural Network for Makeup Recommendation.**|AAAI|Fashion|[Link](https://dl.acm.org/doi/abs/10.5555/3298239.3298377)||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2017|**Exploiting food choice biases for healthier recipe recommendation.**|SIGIR|Food|[Link](https://doi.org/10.1145/3077136.3080826)||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2017|**Yum-me: a personalized nutrient-based meal recommender system.**|TOIS|Food|[Link](https://doi.org/10.1145/3072614)||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2017|**What your images reveal: Exploiting visual contents for point-of-interest recommendation.**|WWW|POI|[Link](https://doi.org/10.1145/3038912.3052638)||(Instagram) <br> [ImageNet](http://www.image-net.org/)||
|2017|**A hybrid recommendation system considering visual information for predicting favorite restaurants.**|WWW|restaurant|[Link](https://doi.org/10.1007/s11280-017-0437-1)||source NA||
|2015|**Harvesting Multiple Sources for User Profile Learning: aBig Data Study.**|ICMR|POI|[Link](https://dl.acm.org/doi/pdf/10.1145/2671188.2749381)||[NUS-MSS](http://nusmultisource.azurewebsites.net/)||
|2014|**Personalized geo-specific tag recommendation for photos on social websites.**|Tr. MM|tag|[Link](https://doi.org/10.1109/TMM.2014.2302732)||[Flicker API](https://www.flickr.com/services/api/)||
|2011|**Image annotation based on recommendation model.**|SIGIR|tag|[Link](https://doi.org/10.1145/2009916.2010067)||[1. GT database of UW](http://imagedatabase.cs.washington.edu/groundtruth/) <br> [2. MIRFlicker](http://press.liacs.nl/mirflickr/)||
### Video recommendation
### target: movie-related content
| Year  | Title       |Target Item  | Venue    | Link        |Code | Data|
|------|-------|----------|-----------|---------------|-------|-------|
|2019|**Movie Genome: Alleviating New Item Cold Start in Movie Recommendation**| Movie trailer | MTAP | [Link](https://doi.org/10.1007/s11257-019-09221-y)|[Code](https://github.com/MaurizioFD/RecSys2019_DeepLearning_Evaluation)|[MMTF-14K](https://mmprj.github.io/mtrm_dataset/index)||
|2018|**Exploiting Visual Contents in Posters and Still Frames for Movie Recommendation.**| Movie poster + still frame |IEEE Access| [Link](https://doi.org/10.1109/ACCESS.2018.2879971)| |[IMDB](https://www.imdb.com/)||
|2018|**Using visual features and latent factors for movie recommendation.**| Movie trailer | CBRecSys| [Link](https://doi.org/10.1007/s13735-018-0155-1)| | ||
|2018|**Using Visual Features based on MPEG-7 and Deep Learning for Movie Recommendation**| Movie trailer | IJMIR| [Link](https://doi.org/10.1007/s13735-018-0155-1)||[Mise-en-Scène DS: MPEG-7 + CNN](https://www.researchgate.net/publication/317038064_Mise-en-Scene_Dataset_MPEG-7_Visual_Features_of_Movie_Trailers_dataset)||
|2018|**Audio-visual encoding of multimedia content for enhancing movie recommendations.**|Movie trailer | RecSys | [Link](https://doi.org/10.1145/3240323.3240407)||[MMTF-14K](https://mmprj.github.io/mtrm_dataset/index)||
|2016|**Latent factor representations for cold-start video recommendation.**|Movie trailer | RecSys | [Link](https://doi.org/10.1145/2959100.2959172)||1:Video Emotion DS (Av. upon Req.)<br> [2: Amazon Product](https://nijianmo.github.io/amazon/index.html)|
|2016|**Content-based video recommendation system based on stylistic visual features.**| Movie trailer | JoDS| [Link](https://doi.org/10.1007/s13740-016-0060-9)| | ||
|2013|**Affective recommendation of movies based on selected connotative features.**|Movie Scenes| RecSys | [Link](https://doi.org/10.1109/TCSVT.2012.2211935)||[Gratest film scenes](https://www.filmsite.org/scenes.html)|
|2013|**VideoTopic: Content-Based Video Recommendation Using a Topic Model**| Movie trailer | MTAP | [Link](https://doi.org/10.1109/ISM.2013.41)||IMDB + [YouTube](http://www.youtube.com)||

### User-generated video
| Year  | Title       |Target Item  | Venue    |Code | Data|
|------|-------|----------|--------|-------|-------|
|2018|**[LGA: latent genre aware micro-video recommendation on social media.](https://doi.org/10.1007/s11042-017-4827-2)**|![elearning-1](https://user-images.githubusercontent.com/12104758/83068526-c461ad00-a068-11ea-8766-1e4ed5235f4f.png)|MTAP|[Twitter Streaming API](https://dev.twitter.com/streaming/overview)||
|2015|**[Mining Affective Context in Short Films for Emotion-Aware Recommendation.](https://doi.org/10.1145/2700171.2791042)**|![elearning-1](https://user-images.githubusercontent.com/12104758/83068526-c461ad00-a068-11ea-8766-1e4ed5235f4f.png)|HT||(Av. upon Req.)||
|2014|**[What videos are similar with you?: Learning a common attributed representation for video recommendation](https://doi.org/10.1145/2647868.2654946)**|![elearning-1](https://user-images.githubusercontent.com/12104758/83068526-c461ad00-a068-11ea-8766-1e4ed5235f4f.png)|ACM MM|[Tencent Weibo](http://t.qq.com/)||
|2013|**[Personalized video recommendation based on cross-platform user modeling.](https://doi.org/10.1109/ICME.2013.6607513)**|![elearning-1](https://user-images.githubusercontent.com/12104758/83068526-c461ad00-a068-11ea-8766-1e4ed5235f4f.png)| ICME ||[Google+/YouTube](https://www.youtube.com)||
|2012|**[On video recommendation over social network.](https://doi.org/10.1007/978-3-642-27355-1_16)**|![elearning-1](https://user-images.githubusercontent.com/12104758/83068526-c461ad00-a068-11ea-8766-1e4ed5235f4f.png)|MMM ||[Facebook](www.facebook.com)||
|2012|**[Personalized video recommendation based on viewing history with the study on youtube.](https://doi.org/10.1145/2382336.2382382)**|![elearning-1](https://user-images.githubusercontent.com/12104758/83068526-c461ad00-a068-11ea-8766-1e4ed5235f4f.png)|ICIMCS ||[YouTube](https://www.youtube.com)||
|2011|**[Contextual video recommendation by multimodal relevance and user feedback.](https://doi.org/10.1145/1961209.1961213)**|![elearning-1](https://user-images.githubusercontent.com/12104758/83068526-c461ad00-a068-11ea-8766-1e4ed5235f4f.png)|ACM TOIS ||[MSN Video](https://www.msn.com/en-us/Video/?mkt=en-us&tab=soapbox/)||
|2007|**[Online video recommendation based on multimodal fusion and relevance feedback.](https://dl.acm.org/doi/10.1145/1282280.1282290)**|![elearning-1](https://user-images.githubusercontent.com/12104758/83068526-c461ad00-a068-11ea-8766-1e4ed5235f4f.png)|CIVR|--|[MSN Soapbox](http://soapbox.msn.com/)(NA)||


## Contact
For questions, please feel free to contact us at <deldjooy@acm.org>.

## Authors:
* Yashar Deldjoo <deldjooy@acm.org> , <yashar.deldjoo@poliba.it>
* Markus Schedl <markus.schedl@jku.at>
* Paolo Cremonesi <paolo.cremonesi@polimi.it>
* Gabriella Pasi <gabriella.pasi@unimib.it>


