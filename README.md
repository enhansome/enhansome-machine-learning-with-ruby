<img title="Awesome Machine Learning with Ruby" alt="Awesome Machine Learning with Ruby" src="header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) ⭐ 496,553 | 🐛 100 | 📅 2026-06-30 [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

\[[RubyNLP](https://github.com/arbox/nlp-with-ruby) ⭐ 1,075 | 🐛 7 | 🌐 Ruby | 📅 2023-06-27 |
[RubyDataScience](https://github.com/arbox/data-science-with-ruby) ⭐ 721 | 🐛 1 | 🌐 Ruby | 📅 2023-07-19 |
[RubyInterop](https://github.com/arbox/ruby-interoperability) ⭐ 41 | 🐛 1 | 🌐 Ruby | 📅 2020-11-16]

# Awesome Machine Learning with Ruby with stars

> Curated List of Ruby Machine Learning Links and Resources

[Machine Learning][ml] is a field of [Computational Science][cs] -
often nested under [AI][ai] research - with many practical
applications due to the ability of resulting algorithms to
systematically implement a specific solution without explicit
programmer's instructions. Obviously many algorithms need a definition
of [features][fe] to look at or a biggish [training set][ts] of data to derive the
solution from.

This curated list comprises [*awesome*][awesome] libraries,
data sources, tutorials and presentations about [Machine Learning][ml]
utilizing the [Ruby][ruby] programming language.

A lot of useful resources on this list come from the development by
[The Ruby Science Foundation][sciruby], our [contributors][contributors] and
our own day to day work on various ML applications.

:sparkles: Every [contribution](contributing.md) is welcome! Add links through pull
requests or create an issue to start a discussion.

Follow us on [Twitter](https://twitter.com/NonWebRuby) and please spread
the word using the `#RubyML` hash tag!

<!-- nodoc -->

## Contents

<!-- toc -->

* [:sparkles: Tutorials](#sparkles-tutorials)
* [Machine Learning Libraries](#machine-learning-libraries)
  * [Frameworks](#frameworks)
  * [Neural networks](#neural-networks)
  * [Deep Learning](#deep-learning)
  * [Kernel methods](#kernel-methods)
  * [Evolutionary algorithms](#evolutionary-algorithms)
  * [Bayesian methods](#bayesian-methods)
  * [Decision trees](#decision-trees)
  * [Clustering](#clustering)
  * [Linear classifiers](#linear-classifiers)
  * [Statistical models](#statistical-models)
  * [Gradient boosting](#gradient-boosting)
  * [Vector search](#vector-search)
* [Applications of machine learning](#applications-of-machine-learning)
* [Data structures](#data-structures)
* [Data visualization](#data-visualization)
* [Articles, Posts, Talks, and Presentations](#articles-posts-talks-and-presentations)
* [Projects and Code Examples](#projects-and-code-examples)
* [Heroku buildpacks](#heroku-buildpacks)
* [Books, Blogs, Channels](#books-blogs-channels)
* [Community](#community)
* [Related Resources](#related-resources)
* [License](#license)

<!-- tocstop -->

<!-- doc -->

## :sparkles: Tutorials

Please help us to fill out this section! :smiley:

* [Teaching an AI to play a simple game using Q-Learning in Ruby](https://www.practicalai.io/teaching-ai-play-simple-game-using-q-learning/) <sup>\[[code](https://github.com/daugaard/q-learning-simple-game) ⭐ 36 | 🐛 1 | 🌐 Ruby | 📅 2017-09-03]</sup>
* [Teaching a Neural Network to play a game using Q-Learning in Ruby](https://www.practicalai.io/teaching-a-neural-network-to-play-a-game-with-q-learning/) <sup>\[[code](https://github.com/daugaard/q-learning-simple-game/tree/neuralnetwork) ⭐ 36 | 🐛 1 | 🌐 Ruby | 📅 2017-09-03]</sup>
* [How to *evolve* neural networks in Ruby using the Machine Learning Workbench](https://github.com/giuse/machine_learning_workbench/blob/master/examples/neuroevolution.rb) ⭐ 20 | 🐛 1 | 🌐 Ruby | 📅 2021-11-02
* [How to implement simple binary classification using a Neural Network in Ruby](https://www.practicalai.io/implementing-simple-classification-using-neural-network-in-ruby/) <sup>\[[code](https://github.com/daugaard/example-neural-network) ⭐ 10 | 🐛 0 | 🌐 Ruby | 📅 2017-07-03]</sup>
* [How to implement classification using a SVM in Ruby](https://www.practicalai.io/implementing-classification-using-a-svm-in-ruby/) <sup>\[[code](https://github.com/daugaard/example-svm) ⭐ 6 | 🐛 0 | 🌐 Ruby | 📅 2017-07-15]</sup>
* [How to implement linear regression in Ruby](https://www.practicalai.io/implementing-linear-regression-using-ruby/) <sup>\[[code](https://github.com/daugaard/example-linear-regression) ⭐ 5 | 🐛 0 | 🌐 Ruby | 📅 2017-06-14]</sup>
* [Using the Python scikit-learn machine learning library in Ruby using PyCall](https://www.practicalai.io/using-scikit-learn-machine-learning-library-in-ruby-using-pycall/) <sup>\[[code](https://github.com/daugaard/scikit-learn-from-ruby) ⭐ 4 | 🐛 0 | 🌐 Ruby | 📅 2017-09-17]</sup>
* [Unsupervised learning using k-means clustering in Ruby](https://www.practicalai.io/unsupervised-learning-using-k-means-clustering-in-ruby/) <sup>\[[code](https://github.com/daugaard/example-kmeans-clustering) ⭐ 0 | 🐛 0 | 🌐 Ruby | 📅 2017-07-29]</sup>
* [Ruby neural networks](https://www.honeybadger.io/blog/ruby-neural-networks/)
* [How to implement classification using logistic regression in Ruby](https://www.practicalai.io/implementing-classification-using-logistic-regression-in-ruby/)

## Machine Learning Libraries

[Machine Learning][ml] algorithms in pure Ruby or written in other
programming languages with appropriate bindings for Ruby.

### Frameworks

* [aws-sdk-machinelearning](https://github.com/aws/aws-sdk-ruby) ⭐ 3,656 | 🐛 26 | 🌐 Ruby | 📅 2026-08-14 -
  Machine Learning API of the Amazon Web Services.
* [ruby-openai](https://github.com/alexrudall/ruby-openai) ⭐ 3,224 | 🐛 53 | 🌐 Ruby | 📅 2026-05-01 - OpenAI API wrapper
* [shogun](https://github.com/shogun-toolbox/shogun) ⭐ 3,079 | 🐛 424 | 🌐 C++ | 📅 2023-12-19 - Polyfunctional and mature
  machine learning toolbox with [Ruby bindings](https://github.com/shogun-toolbox/shogun/tree/develop/src/interfaces/ruby) ⭐ 3,079 | 🐛 424 | 🌐 C++ | 📅 2023-12-19.
* [LangChain.rb](https://github.com/andreibondarev/langchainrb) ⭐ 1,989 | 🐛 79 | 🌐 Ruby | 📅 2026-08-14 -
  Build ML/AI-supercharged applications with Ruby's LangChain.
* [rumale](https://github.com/yoshoku/rumale) ⭐ 914 | 🐛 0 | 🌐 Ruby | 📅 2026-08-05 -
  Machine Learninig toolkit in Ruby with wide range of implemented algorithms
  (SVM, Logistic Regression, Linear Regression, Random Forest etc.) and
  interfaces similar to [Scikit-Learn][scikit] in Python.
* [ai4r](https://github.com/SergioFierens/ai4r) ⭐ 721 | 🐛 0 | 🌐 Ruby | 📅 2025-07-18 -
  Artificial Intelligence for Ruby.
* [eps](https://github.com/ankane/eps) ⭐ 692 | 🐛 0 | 🌐 Ruby | 📅 2026-06-29 - Bayesian Classification and Linear Regression with exports
  using [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) and an alternative backend using [GSL][gsl].
* [classifier-reborn](https://github.com/jekyll/classifier-reborn) ⭐ 559 | 🐛 28 | 🌐 Ruby | 📅 2024-05-27 -
  General classifier module to allow Bayesian and other types of classifications. <sup>\[[dep: GLS](#gls)]</sup>
* [azure\_mgmt\_machine\_learning](https://github.com/Azure/azure-sdk-for-ruby) ⚠️ Archived -
  Machine Learning API of the Microsoft Azure.
* [Deep NeuroEvolution](https://github.com/giuse/DNE) ⭐ 126 | 🐛 3 | 🌐 Ruby | 📅 2019-12-31 -
  Experimental setup based on the [machine\_learning\_workbench](https://github.com/giuse/machine_learning_workbench) ⭐ 20 | 🐛 1 | 🌐 Ruby | 📅 2021-11-02
  towards searching for deep neural networks (rather than training) using evolutionary algorithms. Applications to the
  [OpenAI Gym](https://github.com/openai/gym) ⚠️ Archived using [PyCall](https://github.com/mrkn/pycall.rb) ⭐ 1,116 | 🐛 51 | 🌐 C | 📅 2026-07-27.
* [scoruby](https://github.com/asafschers/scoruby) ⭐ 70 | 🐛 4 | 🌐 Ruby | 📅 2022-10-19 -
  Ruby scoring API for [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) (Predictive Model Markup Language).
* [weka](https://github.com/paulgoetze/weka-jruby) ⭐ 65 | 🐛 0 | 🌐 Ruby | 📅 2026-06-24 -
  JRuby bindings for Weka, different ML algorithms implemented through Weka.
* [Instruct](https://github.com/instruct-rb/instruct) ⭐ 49 | 🐛 1 | 🌐 Ruby | 📅 2025-02-07 - Inspired by Guidance; weave code, prompts and completions together to instruct LLMs to do what you want.
* [machine\_learning\_workbench](https://github.com/giuse/machine_learning_workbench) ⭐ 20 | 🐛 1 | 🌐 Ruby | 📅 2021-11-02 -
  Growing machine learning framework written in pure Ruby, high performance computing using
  [Numo](https://github.com/ruby-numo/), CUDA bindings through [Cumo](https://github.com/sonots/cumo) ⭐ 99 | 🐛 8 | 🌐 C | 📅 2026-08-16.
  Currently implementating neural networks, evolutionary strategies, vector quantization, and plenty of
  examples and utilities.
* [rblearn](https://github.com/himkt/rblearn) ⭐ 2 | 🐛 0 | 🌐 Ruby | 📅 2016-08-03 - Feature Extraction and Crossvalidation library.
* [data\_modeler](https://github.com/giuse/data_modeler) ⭐ 1 | 🐛 1 | 🌐 Ruby | 📅 2017-06-28 -
  Model your data with machine learning. Ample test coverage, examples to start fast, complete documentation. Production ready since 1.0.0.

### Neural networks

* [ruby-fann](https://github.com/tangledpath/ruby-fann) ⭐ 506 | 🐛 1 | 🌐 C | 📅 2024-03-25 -
  Ruby bindings to the [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
* [neural-net-ruby](https://github.com/gbuesing/neural-net-ruby) ⭐ 127 | 🐛 0 | 🌐 Ruby | 📅 2017-07-02 -
  Neural network written in Ruby.
* [tlearn-rb](https://github.com/josephwilk/tlearn-rb) ⭐ 97 | 🐛 3 | 🌐 C | 📅 2018-01-04 -
  Recurrent Neural Network library for Ruby.
* [brains](https://github.com/jedld/brains-jruby) ⭐ 60 | 🐛 0 | 🌐 Ruby | 📅 2017-03-20 -
  Feed-forward neural networks for JRuby based on
  [brains](https://github.com/jedld/brains) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2017-03-20.
* [cerebrum](https://github.com/irfansharif/cerebrum) ⭐ 35 | 🐛 0 | 🌐 Ruby | 📅 2019-03-03 -
  Experimental implementation for Artificial Neural Networks in Ruby.
* [machine\_learning\_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/neural_network) ⭐ 20 | 🐛 1 | 🌐 Ruby | 📅 2021-11-02 -
  Framework including pure-Ruby implementation of both feed-forward and recurrent neural networks
  (fully connected). Training available using neuroevolution (Natural Evolution Strategies algorithms).
* [rann](https://github.com/mikecmpbll/rann) ⭐ 3 | 🐛 6 | 🌐 Ruby | 📅 2017-12-11 -
  Flexible Ruby ANN implementation with backprop (through-time, for recurrent
  nets), gradient checking, adagrad, and parallel batch execution.

### Deep learning

* [torch-rb](https://github.com/ankane/torch-rb) ⭐ 837 | 🐛 5 | 🌐 Ruby | 📅 2026-07-08 - Ruby bindings for [LibTorch](https://github.com/pytorch/pytorch) ⭐ 102,429 | 🐛 17,326 | 🌐 Python | 📅 2026-08-16
  using [rice](https://github.com/jasonroelofs/rice) ⭐ 417 | 🐛 2 | 🌐 C++ | 📅 2026-05-05.
* [tensorflow](https://github.com/somaticio/tensorflow.rb) ⭐ 832 | 🐛 15 | 🌐 Ruby | 📅 2022-01-10 - Ruby bindings for [TensorFlow](https://www.tensorflow.org/).
* [tensor\_stream](https://github.com/jedld/tensor_stream) ⭐ 506 | 🐛 2 | 🌐 Ruby | 📅 2020-12-26 -
  Ground-up and standalone reimplementation of TensorFlow for Ruby.
* [red-chainer](https://github.com/red-data-tools/red-chainer) ⭐ 103 | 🐛 5 | 🌐 Ruby | 📅 2022-01-05 - Deep learning framework for Ruby.
* [mxnet](https://github.com/mrkn/mxnet.rb) ⭐ 48 | 🐛 22 | 🌐 Ruby | 📅 2020-12-22 - Ruby bindings for [mxnet](https://mxnet.apache.org/).
* [ruby-dnn](https://github.com/unagiootoro/ruby-dnn) ⭐ 46 | 🐛 3 | 🌐 Ruby | 📅 2023-07-04 - Simple deep learning for Ruby.

### Kernel methods

* [rb-libsvm](https://github.com/febeling/rb-libsvm) ⭐ 279 | 🐛 2 | 🌐 C++ | 📅 2023-12-07 -
  Support Vector Machines with Ruby and the [LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) library. <sup>\[[dep: bundled](#bundled)]</sup>

### Evolutionary algorithms

* [machine\_learning\_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/optimizer/natural_evolution_strategies) ⭐ 20 | 🐛 1 | 🌐 Ruby | 📅 2021-11-02 -
  Framework including pure-Ruby implementations of Natural Evolution Strategy algorithms
  (black-box optimization), specifically Exponential NES (XNES),
  Separable NES (sNES), Block-Diagonal NES (BDNES) and more.
  Applications include neural network search/training (neuroevolution).
* [simple\_ga](https://github.com/giuse/simple_ga) ⭐ 11 | 🐛 0 | 🌐 Ruby | 📅 2016-10-26 -
  Simplest Genetic Algorithms implementation in Ruby.

### Bayesian methods

* [nbayes](https://github.com/oasic/nbayes) ⭐ 155 | 🐛 3 | 🌐 Ruby | 📅 2024-02-12 -
  Full-featured, Ruby implementation of Naive Bayes.
* [naive\_bayes](https://github.com/reddavis/Naive-Bayes) ⭐ 49 | 🐛 6 | 🌐 Ruby | 📅 2012-01-29 -
  Simple Naive Bayes classifier.
* [linnaeus](https://github.com/djcp/linnaeus) ⭐ 37 | 🐛 2 | 🌐 Ruby | 📅 2015-12-26 -
  Redis-backed Bayesian classifier.

### Decision trees

* [decisiontree](https://github.com/igrigorik/decisiontree) ⭐ 1,489 | 🐛 10 | 🌐 Ruby | 📅 2018-10-31 -
  Decision Tree ID3 Algorithm in pure Ruby. <sup>\[[dep: GraphViz](#graphviz) |
  [post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.

### Clustering

* [k\_means](https://github.com/reddavis/K-Means) ⚠️ Archived -
  Attempting to build a fast, memory efficient K-Means program.
* [kmeans-clusterer](https://github.com/gbuesing/kmeans-clusterer) ⭐ 99 | 🐛 8 | 🌐 Ruby | 📅 2020-09-21 -
  k-means clustering in Ruby.
* [knn](https://github.com/reddavis/knn) ⭐ 37 | 🐛 4 | 🌐 Ruby | 📅 2020-05-22 -
  Simple K Nearest Neighbour Algorithm.

### Linear classifiers

* [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) ⭐ 83 | 🐛 5 | 🌐 C++ | 📅 2023-06-27 -
  Ruby interface to LIBLINEAR (much more efficient than LIBSVM for text classification).
* [liblinear-ruby](https://github.com/kei500/liblinear-ruby) ⭐ 82 | 🐛 3 | 🌐 C++ | 📅 2019-03-29 -
  Ruby interface to LIBLINEAR using SWIG.

### Statistical models

* [lda-ruby](https://github.com/ealdent/lda-ruby) ⭐ 134 | 🐛 0 | 🌐 Ruby | 📅 2026-05-04 -
  Ruby implementation of the [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
  (Latent Dirichlet Allocation) for automatic Topic Modelling and Document Clustering.
* [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) ⭐ 31 | 🐛 1 | 🌐 Ruby | 📅 2021-01-13 -
  Naive Bayes text classification implementation as an OmniCat classifier strategy. <sup>\[[dep: bundled](#bundled)]</sup>
* [omnicat](https://github.com/mustafaturan/omnicat) ⭐ 11 | 🐛 0 | 🌐 Ruby | 📅 2021-01-13 -
  Generalized rack framework for text classifications.
* [maxent\_string\_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) ⭐ 9 | 🐛 0 | 🌐 Ruby | 📅 2009-07-06 -
  JRuby maximum entropy classifier for string data, based on the OpenNLP Maxent framework.
* [rtimbl](https://github.com/maspwr/rtimbl) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2009-10-23 -
  Memory based learners from the Timbl framework.

### Gradient boosting

* [xgb](https://github.com/ankane/xgb) ⭐ 121 | 🐛 0 | 🌐 Ruby | 📅 2026-08-05 —
  Ruby bindings for XGBoost. <sup>\[[dep: XGBoost](#xgboost)]</sup>
* [lightgbm](https://github.com/ankane/lightgbm) ⭐ 84 | 🐛 0 | 🌐 Ruby | 📅 2026-07-18 —
  Ruby bindings for LightGBM. <sup>\[[dep: LightGBM](#lightgbm)]</sup>
* [xgboost](https://github.com/PairOnAir/xgboost-ruby) ⭐ 20 | 🐛 0 | 🌐 Ruby | 📅 2018-04-12 —
  Ruby bindings for XGBoost. <sup>\[[dep: XGBoost](#xgboost)]</sup>

### Vector search

* [flann](https://github.com/mariusmuja/flann) ⭐ 2,373 | 🐛 298 | 🌐 C++ | 📅 2024-07-29 -
  Ruby bindings for the [FLANN](https://github.com/flann-lib/flann) ⭐ 2,373 | 🐛 298 | 🌐 C++ | 📅 2024-07-29 (Fast Library for Approximate Nearest Neighbors). <sup>\[[flann](#flann)]</sup>
* [pinecone](https://github.com/ScotterC/pinecone) ⭐ 67 | 🐛 2 | 🌐 Ruby | 📅 2026-03-18 —
  Ruby client for Pinecone Vector DB.
* [qdrant-ruby](https://github.com/andreibondarev/qdrant-ruby) ⭐ 61 | 🐛 1 | 🌐 Ruby | 📅 2026-08-12 —
  Ruby wrapper for the Qdrant vector search database API.
* [weaviate-ruby](https://github.com/andreibondarev/weaviate-ruby) ⭐ 58 | 🐛 9 | 🌐 Ruby | 📅 2026-04-17 —
  Ruby wrapper for the Weaviate vector search database API.
* [ngt-ruby](https://github.com/ankane/ngt-ruby) ⭐ 53 | 🐛 0 | 🌐 Ruby | 📅 2026-04-02 -
  Ruby bindings for the [NGT](https://github.com/yahoojapan/NGT) ⭐ 1,370 | 🐛 30 | 🌐 C++ | 📅 2026-07-27 (Neighborhood Graph and Tree for Indexing High-dimensional data).
* [annoy-rb](https://github.com/yoshoku/annoy.rb) ⭐ 37 | 🐛 3 | 🌐 C++ | 📅 2026-06-18 -
  Ruby bindings for the [Annoy](https://github.com/spotify/annoy) ⭐ 14,288 | 🐛 84 | 🌐 C++ | 📅 2025-10-29 (Approximate Nearest Neighbors Oh Yeah).
* [milvus](https://github.com/andreibondarev/milvus) ⭐ 33 | 🐛 1 | 🌐 Ruby | 📅 2025-03-31 —
  Ruby client for Milvus Vector DB.
* [hnswlib.rb](https://github.com/yoshoku/hnswlib.rb) ⭐ 15 | 🐛 3 | 🌐 C++ | 📅 2026-08-06 -
  Ruby bindings for the [Hnswlib](https://github.com/nmslib/hnswlib) ⭐ 5,309 | 🐛 286 | 🌐 C++ | 📅 2026-03-28 that implements approximate nearest neighbor search with Hierarchical Navigable Small World graphs.

## Applications of machine learning

* [phashion](https://github.com/westonplatter/phashion) ⭐ 711 | 🐛 30 | 🌐 Ruby | 📅 2025-10-23 -
  Ruby wrapper around pHash, the perceptual hash library for detecting duplicate multimedia files. <sup>\[[ImageMagick](#imagemagick) | [libjpeg](#libjpeg)]</sup>

## Data structures

If you're going to implement your own ML algorithms you're probably interested
in storing your feature sets efficiently. Look for appropriate
[data structures](https://github.com/arbox/data-science-with-ruby#data-structures) ⭐ 721 | 🐛 1 | 🌐 Ruby | 📅 2023-07-19
in our [Data Science with Ruby][ds-with-ruby] list.

## Data visualization

Please refer to the [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization) ⭐ 721 | 🐛 1 | 🌐 Ruby | 📅 2023-07-19
section on the [Data Science with Ruby][ds-with-ruby] list.

## Articles, Posts, Talks, and Presentations

* 2022
  * *Discover Machine Learning in Ruby* by [Justin Bowen](https://twitter.com/TonsOfFun111) <sup>\[[video](https://www.youtube.com/watch?v=HPbizNgcyFk)]</sup>

* 2019
  * *TensorStream: Bringing Machine Learning to Ruby* by [Joseph Emmanuel Dayo](https://www.linkedin.com/in/jdayo/) <sup>\[[post](https://medium.com/@joseph.dayo/tensorstream-bringing-machine-learning-to-ruby-114582060e3d)]</sup>
  * *Easy machine learning with Ruby using SVMKit* by [@kojix](https://twitter.com/kojix2dayo) <sup>\[[post](https://dev.to/kojix2/easy-machine-learning-with-ruby-using-svmkit-4n86)]</sup>

* 2018
  * *Deep Learning Programming on Ruby* by [Kenta Murata](https://twitter.com/mrkn)
    & [Yusaku Hatanaka ](https://twitter.com/hatappi) <sup>\[[slides](https://speakerdeck.com/mrkn/deep-learning-programming-on-ruby) |
    [page](https://rubykaigi.org/2018/presentations/mrkn.html)]</sup>
  * *How to use trained Keras and TensorFlow machine learning models within Ruby on Rails* by [Denis Sellu](https://twitter.com/denis_sellu) <sup>\[[post](https://www.cookieshq.co.uk/posts/how-to-use-trained-keras-and-tensorflow-machine-learning-models-within-ruby-on-rails)]</sup>

* 2017
  * *Scientific Computing on JRuby* by [Prasun Anand](https://twitter.com/prasun_anand) <sup>\[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
  * *Is it Food? An Introduction to Machine Learning* by [Matthew Mongeau](https://twitter.com/halogenandtoast) <sup>\[[video](https://www.youtube.com/watch?v=8G709hKkthY) |
    [slides](https://www.slideshare.net/halogenandtoast/is-it-food)]</sup>
  * *Bayes is BAE* by [Richard Schneeman](https://twitter.com/schneems) <sup>\[[video](https://www.youtube.com/watch?v=bQSzZrDDV80) |
    [slides](https://speakerdeck.com/schneems/bayes-is-bae)]</sup>
  * *Ruby Roundtable: Machine Learning in Ruby* by [RubyThursday](https://rubythursday.com/) <sup>\[[video](https://www.youtube.com/watch?v=ScIFARN0jCo)]</sup>

* 2016
  * *Practical Machine Learning with Ruby* by [Jordan Hudgens](https://twitter.com/jordanhudgens) <sup>\[[tutorial](https://www.crondose.com/2016/12/practical-machine-learning-ruby/)]</sup>
  * *Deep Learning: An Introduction for Ruby Developers* by [Geoffrey Litt](https://twitter.com/geoffreylitt) <sup>\[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  * *How I made a pure-Ruby word2vec program more than 3x faster* by [Kei Sawada](https://twitter.com/remore) <sup>\[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  * *Dōmo arigatō, Mr. Roboto: Machine Learning with Ruby* by [Eric Weinstein](https://twitter.com/ericqweinstein) <sup>\[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) |
    [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
  * *Building a Recommendation Engine with Machine Learning Techniques* by [Brian Sam-Bodden](https://twitter.com/bsbodden) <sup>\[[video](https://www.youtube.com/watch?v=SRnM_P_ygqI)]</sup>
  * :sparkles: *SciRuby Machine Learning: Current Status and Future* by [Kenta Murata](https://twitter.com/mrkn) <sup>\[[slides](https://speakerdeck.com/mrkn/sciruby-machine-learning-current-status-and-future) |
    [video: jp](https://www.youtube.com/watch?v=gfQ8XEy7vO4)]</sup>
  * *Ruby Roundtable: Intro to Tensorflow* by [RubyThursday](https://rubythursday.com/) <sup>\[[video](https://www.youtube.com/watch?v=pYC5mXHUWkc)]</sup>

* 2015
  * *Machine Learning made simple with Ruby* by [Lorenzo Masini](https://twitter.com/rugginoso) <sup>\[[post](https://www.leanpanda.com/blog/2015-08-24-machine-learning-automatic-classification/)]</sup>
  * *Using Ruby Machine Learning to Find Paris Hilton Quotes* by [Rick Carlino](https://github.com/RickCarlino) <sup>\[[tutorial](https://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>

* 2014
  * *Test Driven Neural Networks* by [Matthew Kirk](https://twitter.com/mjkirk) <sup>\[[video](https://www.youtube.com/watch?v=ppf8m-3uXvU\&t=36s)]</sup>
  * *Five machine learning techniques that you can use in your Ruby apps today* by [Benjamin Curtis](https://twitter.com/stympy) <sup>\[[video](https://www.youtube.com/watch?v=crziu7dk6Vw) |
    [slides](https://speakerdeck.com/stympy/machine-learning-techniques)]</sup>
  * *Machine Learning for Fun and Profit* by [John Paul Ashenfelter](https://twitter.com/johnashenfelter) <sup>\[[video](https://www.youtube.com/watch?v=KC5MtKHm1O4)]</sup>

* 2013
  * *Sentiment Analysis using Support Vector Machines in Ruby* by [Matthew Kirk](https://twitter.com/mjkirk) <sup>\[[video](https://www.youtube.com/watch?v=iSug6CgxWxc) |
    [code](https://github.com/hexgnu/sentiment_analyzer) ⭐ 12 | 🐛 0 | 🌐 CSS | 📅 2013-11-28]</sup>
  * *Recommender Systems with Ruby* by [Marcel Caraciolo](https://twitter.com/marcelcaraciolo) <sup>\[[slides](https://www.slideshare.net/marcelcaraciolo/recommender-systems-with-ruby-adding-machine-learning-statistics-etc)]</sup>
  * *Detecting Faces with Ruby: FFI in a Nutshell* by [Marc Berszick]() <sup>\[[post](https://www.sitepoint.com/detecting-faces-with-ruby-ffi-in-a-nutshell/)]</sup>

* 2012
  * *Machine Learning with Ruby, Part One* by [Vasily Vasinov](https://twitter.com/vasinov) <sup>\[[tutorial](https://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
  * *Recurrent Neural Networks in Ruby* by [Joseph Wilk](https://twitter.com/josephwilk) <sup>\[[post](http://blog.josephwilk.net/ruby/recurrent-neural-networks-in-ruby.html)]</sup>
  * *Recommendation Engines using Machine Learning, and JRuby* by [Matthew Kirk](https://twitter.com/mjkirk) <sup>\[[video](https://www.youtube.com/watch?v=hsZcrlbBg_0)]</sup>
  * *Practical Machine Learning and Rails* by [Andrew Cantino](https://twitter.com/tectonic)
    and [Ryan Stout](https://twitter.com/ryanstout) <sup>\[[video](https://www.youtube.com/watch?v=vy_zQ1-F0JI)]</sup>

* 2011
  * *Clustering in Ruby* by [Colin Drake](https://twitter.com/colinfdrake) <sup>\[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)]</sup>
  * *Text Classification using Support Vector Machines in Ruby* by [Rimas Silkaitis](https://twitter.com/neovintage) <sup>\[[post](http://neovintage.org/2011/11/14/text-classification-using-support/)]</sup>

* 2010
  * *bayes\_motel – Bayesian classification for Ruby* by [Mike Perham](https://twitter.com/mperham) <sup>\[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
  * *Intelligent Ruby: Getting Started with Machine Learning* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[video](https://vimeo.com/22513786)]</sup>

* 2009

* 2008
  * *Support Vector Machines (SVM) in Ruby* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>

* 2007
  * *Decision Tree Learning in Ruby* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>

## Projects and Code Examples

* [simple\_ga](https://github.com/giuse/simple_ga) ⭐ 11 | 🐛 0 | 🌐 Ruby | 📅 2016-10-26 -
  Basic (working) demo of Genetic Algorithms in Ruby.
* [Handwritten Digits Recognition](https://github.com/jdrzj/handwritten-digits-recognition) ⭐ 6 | 🐛 0 | 🌐 Ruby | 📅 2021-03-09 -
  Handwritten digits recognition using Neural Networks and Ruby.
* [Wine Clustering](https://github.com/hexgnu/wine_clustering) ⭐ 0 | 🐛 0 | 🌐 Ruby | 📅 2014-04-02 -
  Wine quality estimations clustered with different algorithms.

## Heroku buildpacks

* [ImageMagick buildpack](https://github.com/mcollina/heroku-buildpack-imagemagick) ⭐ 46 | 🐛 9 | 🌐 Shell | 📅 2015-01-31
* [GSL and Ruby buildpack](https://github.com/tomwolfe/heroku-buildpack-gsl-ruby) ⭐ 3 | 🐛 3 | 🌐 Ruby | 📅 2020-08-15
* [OpenCV and Ruby buildpack](https://github.com/lilibethdlc/heroku-buildpack-ruby-opencv) ⭐ 3 | 🐛 0 | 🌐 Ruby | 📅 2014-04-29

## Books, Blogs, Channels

* [Kirk, Matthew](https://twitter.com/mjkirk).
  *Thoughtful Machine Learning: A Test-Driven Approach*. O'Reilly, 2014. <sup>\[[Amazon](https://www.amazon.com/Thoughtful-Machine-Learning-Test-Driven-Approach/dp/1449374069) |
  [code](https://github.com/thoughtfulml/examples) ⭐ 128 | 🐛 9 | 🌐 Ruby | 📅 2023-04-12]</sup>
* [Practical Artificial Intelligence](https://www.practicalai.io/) -
  Blog about Artificial Intelligence and Machine Learning with tutorials and code samples in Ruby.

## Community

* [SciRuby Mailing List](https://groups.google.com/forum/#!forum/sciruby-dev)
* [SciRuby Slack](https://sciruby.slack.com/)
* [Red Data Gitter](https://gitter.im/red-data-tools/)
* [Reddit](https://www.reddit.com/r/MachineLearning/search?q=Ruby\&restrict_sr=on)
* [Stack Overflow](https://stackoverflow.com/search?q=machine+learning+ruby)
* [Twitter](https://twitter.com/search?q=Machine%20Learning%20Ruby\&src=typd)
* [NonWebRuby](https://twitter.com/NonWebRuby)
* [Ruby AI Builders Discord](https://discord.gg/zDyFJFBTGB)
* [X Ruby AI group](https://twitter.com/i/communities/1709211359039078677)
* [Mastodon Ruby AI and Data group](https://ruby.social/@Ruby_AI_and_Data@chirp.social)

## Related Resources

* <a name="xgboost"></a>
  [XGBoost](https://github.com/dmlc/xgboost) ⭐ 28,659 | 🐛 419 | 🌐 C++ | 📅 2026-08-15
* <a name="lightgbm"></a>
  [LightGBM](https://github.com/microsoft/LightGBM) ⭐ 18,688 | 🐛 512 | 🌐 C++ | 📅 2026-08-14
* [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) ⭐ 17,551 | 🐛 34 | 📅 2026-02-08 -
  Machine Learning with TensorFlow libraries.
* [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) ⭐ 14,139 | 🐛 7 | 📅 2026-08-13 -
  Among other awesome items a short list of NLP related projects.
* [Awesome OCR](https://github.com/kba/awesome-ocr) ⭐ 3,118 | 🐛 64 | 📅 2024-07-06 -
  Multitude of OCR (Optical Character Recognition) resources.
* [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) ⭐ 2,226 | 🐛 19 | 📅 2019-04-02 -
  General List of NLP related resources (mostly not for Ruby programmers).
* [Kiba](https://github.com/thbar/kiba) ⭐ 1,775 | 🐛 0 | 🌐 Ruby | 📅 2026-01-10 -
  Lightweight [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) (Extract, Transform, Load) pipeline.
* [Ruby NLP](https://github.com/diasks2/ruby-nlp) ⭐ 1,285 | 🐛 2 | 📅 2023-03-05 -
  State-of-Art collection of Ruby libraries for NLP.
* [iRuby](https://github.com/SciRuby/iruby) ⭐ 927 | 🐛 49 | 🌐 Ruby | 📅 2026-06-30 - IRuby kernel for Jupyter (formerly IPython).
* [rb-gsl](https://github.com/SciRuby/rb-gsl) ⭐ 104 | 🐛 40 | 🌐 C | 📅 2024-06-03 -
  Ruby interface to the [GNU Scientific Library](https://www.gnu.org/software/gsl/).
* <a name="gls"></a>
  \[GSL (GNU Scientific Library)]\[gls]
* <a name="opencv"></a>
  [OpenCV](https://opencv.org/)
* <a name="empty-lines-around-access-modifier"></a>
  [Graphviz](http://www.graphviz.org/)
* <a name="gnuplot"></a>
  [Gnuplot](http://www.gnuplot.info/)
* <a name="xquartz"></a>
  [X11/XQuartz](https://www.xquartz.org/)
* <a name="imagemagic"></a>
  [ImageMagick](https://www.imagemagick.org/script/index.php)
* <a name="r"></a>
  [R](http://www.r-project.org/)
* <a name="octave"></a>
  [Octave](https://www.gnu.org/software/octave/)
* [scikit-learn algorithm cheatsheet](https://scikit-learn.org/stable/tutorial/machine_learning_map/)
* [Scientific Ruby](http://sciruby.com/) -
  Linear Algebra, Visualization and Scientific Computing for Ruby.
* [The Definitive Guide to Ruby's C API](https://silverhammermba.github.io/emberb/) -
  Modern Reference and Tutorial on Embedding and Extending Ruby using C programming language.

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
`Awesome ML with Ruby` by [Andrei Beliankou](https://github.com/arbox) and
[Contributors][contributors].

To the extent possible under law, the person who associated CC0 with
`Awesome ML with Ruby` has waived all copyright and related or neighboring rights
to `Awesome ML with Ruby`.

You should have received a copy of the CC0 legalcode along with this
work. If not, see <https://creativecommons.org/publicdomain/zero/1.0/>.

<!--- Links --->

[ruby]: https://www.ruby-lang.org/en/

[awesome]: https://github.com/sindresorhus/awesome/blob/master/awesome.md

[change-pr]: https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md

[ml]: https://en.wikipedia.org/wiki/Machine_learning

[ds-with-ruby]: https://github.com/arbox/data-science-with-ruby

[contributors]: https://github.com/arbox/machine-learning-with-ruby/graphs/contributors

[sciruby]: https://github.com/sciruby

[ai]: https://en.wikipedia.org/wiki/Artificial_intelligence

[cs]: https://en.wikipedia.org/wiki/Computational_science

[fe]: https://en.wikipedia.org/wiki/Feature_engineering

[ts]: https://en.wikipedia.org/wiki/Test_set

[gsl]: https://www.gnu.org/software/gsl/

[scikit]: https://scikit-learn.org/stable/index.html

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
