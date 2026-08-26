# Awesome Pharo with stars

A categorized community-driven collection of awesome Pharo libraries, tools, frameworks and software.

## Table of contents

* [Algorithms](#algorithms)
* [Artificial Intelligence and Machine Learning](#artificial-intelligence-and-machine-learning)
* [Books](#books)
* [Code generation](#code-generation)
* [Code quality](#code-quality)
* [Command line](#command-line)
* [Component-Based Architectures](#component-based-architectures)
* [Data interexchange format](#data-interexchange-format)
* [Data structures](#data-structures)
* [Databases](#databases)
* [Datasets](#datasets)
* [Documents generation](#documents-generation)
* [Geography](#geography)
* [Graphics](#graphics)
* [IDE](#ide)
* [Interaction](#interaction)
* [IOT](#iot)
* [Language extensions](#language-extensions)
* [LaTeX](#latex)
* [Loggers](#loggers)
* [Meta-modelling](#meta-modelling)
* [Miscellaneous](#miscellaneous)
* [Network protocols](#network-protocols)
* [Pharo images management](#pharo-images-management)
* [Projects management](#projects-management)
* [Scientific libraries](#scientific-libraries)
* [Software / data analysis](#software--data-analysis)
* [Sound](#sound)
* [System interaction](#system-interaction)
* [Testing](#testing)
* [Tutorials](#tutorials)
* [VCS](#vcs)
* [Videos](#videos)
* [Virtual machine](#virtual-machine)
* [Web](#web)
* [Web API clients](#web-api-clients)

## Algorithms

* [DeepTraverser](https://github.com/pharo-contributions/DeepTraverser) ⭐ 10 | 🐛 0 | 🌐 Smalltalk | 📅 2025-10-10 - Library for traversing object graphs (managing cycles).
* [FuzzySearcher](https://github.com/hernanmd/FuzzySearcher) ⭐ 3 | 🐛 0 | 🌐 Smalltalk | 📅 2024-11-23 - Simplified implementation of ambiguous matching algorithm based on Baeta-Yates, R.A., Gonnet, G.H., Wu, S. and Manber, U.
* [StableMarriage](https://github.com/juliendelplanque/StableMarriage) ⭐ 3 | 🐛 0 | 🌐 Smalltalk | 📅 2018-01-02 - A solver for the stable marriage problem written in Pharo.

## Artificial Intelligence and Machine Learning

The full list of AI and machine learning libraries, tools, and resources for Pharo is available at [pharo-ai / awesome-pharo-ml](https://github.com/pharo-ai/awesome-pharo-ml) ⭐ 70 | 🐛 0 | 📅 2026-04-09.

* [TensorFlow Bindings](https://github.com/PolyMathOrg/libtensorflow-pharo-bindings) ⭐ 32 | 🐛 7 | 🌐 Smalltalk | 📅 2021-05-30 - Allows to use [TensorFlow](https://www.tensorflow.org/) in Pharo.
* [NEAT (NeuroEvolution of Augmenting Topologies)](https://github.com/bergel/NEAT) ⭐ 17 | 🐛 1 | 🌐 Java | 📅 2020-05-08 - A genetic algorithm for evolving artificial neural networks. NEAT is probably the most popular algorithm for neuroevolution.
* [Keras Wrapper](https://github.com/ObjectProfile/KerasWrapper) ⭐ 9 | 🐛 1 | 📅 2023-12-29 - Allows to use [Keras](https://keras.io/) functions within Pharo.
* [pharo-ai / NgramModel](https://github.com/pharo-ai/NgramModel) ⭐ 4 | 🐛 10 | 🌐 Smalltalk | 📅 2025-09-29 - N-gram language model that can be trained to estimate the probability of a next word based on N-1 previous words.
* [pharo-ai / KMeans](https://github.com/pharo-ai/KMeans) ⭐ 3 | 🐛 2 | 🌐 Smalltalk | 📅 2025-09-29 - K-means clustering.
* [pharo-ai / TF-IDF](https://github.com/pharo-ai/TF-IDF) ⭐ 3 | 🐛 0 | 🌐 Smalltalk | 📅 2025-09-29 - Term Frequency - Inverse Document Frequency (TF-IDF), a statistical metric that reflects the importance of a word in a document. Can be used for finding keywords, ranking words by importance, or as a simple way of finding semantic similarity between documents.
* [pharo-ai / APriori](https://github.com/pharo-ai/APriori) ⭐ 2 | 🐛 3 | 🌐 Smalltalk | 📅 2025-09-29 - Fast algorithm for mining frequent sets of items and finding association rules between items in a database of transactions.
* [pharo-ai / NaiveBayesClassifier](https://github.com/pharo-ai/NaiveBayesClassifier) ⭐ 1 | 🐛 3 | 🌐 Smalltalk | 📅 2025-09-29 - Implementation of a multinomial Naive Bayes classifier in Pharo that can be used for simple spam detection and sentiment analysis.

## Books

* <https://books.pharo.org> - Pharo books are a collection of technical or textbook books around Pharo.
* [Agile Artificial Intelligence](https://agileartificialintelligence.github.io) - Agile Artificial Intelligence is a book that covers classical algorithms commonly assimilated as artificial intelligence techniques.
* [Agile Visualization](http://agilevisualization.com) - Visualization made easy in Pharo. It uses the Roassal visualization engine
* [Free online books from Stéphane Ducasse website](http://stephane.ducasse.free.fr/FreeBooks.html) - A collection of free books related to Smalltalk and Pharo.
* [SquareBracketAssociates](https://github.com/SquareBracketAssociates) - Organisation grouping repositories for various books around Pharo.

## Code generation

* [PharoJS](https://github.com/PharoJS/PharoJS) ⭐ 129 | 🐛 40 | 🌐 JavaScript | 📅 2025-11-05 - Converts Pharo code to Javascript.
* [Python3Generator](https://github.com/juliendelplanque/Python3Generator) ⭐ 26 | 🐛 2 | 🌐 Smalltalk | 📅 2024-02-15 - A toolkit to generate Python 3 source code from Pharo.
* [PharoCodeGenerator](https://github.com/juliendelplanque/PharoCodeGenerator) ⭐ 13 | 🐛 9 | 🌐 Smalltalk | 📅 2022-05-15 - Generate Pharo code based on ASTs.
* [XML-XMLWriter](https://github.com/pharo-contributions/XML-XMLWriter) ⭐ 5 | 🐛 0 | 🌐 Smalltalk | 📅 2024-05-28 - Block-based API for XML generation for Pharo.
* [PlainPharoCode](https://github.com/hogoww/PlainPharoCode) ⚠️ Archived - Instead of using String, use Pharo code to define code to generate.
* [Stash](https://github.com/ThalesGroup/Stash) ⭐ 4 | 🐛 0 | 🌐 Smalltalk | 📅 2026-03-24 - A serializer that convert instances into code.
* [VisitorGenerator](https://github.com/hogoww/visitorGenerator) ⚠️ Archived - Generates basic visitor & visit methods for any Pharo classes hierarchy.

## Code quality

* [Chanel](https://github.com/jecisc/Chanel) ⭐ 22 | 🐛 15 | 🌐 Smalltalk | 📅 2026-01-22 - A cleaner for Pharo Smalltalk code.
* [QualityAssistant](https://github.com/Uko/QualityAssistant) ⭐ 16 | 🐛 13 | 🌐 Smalltalk | 📅 2017-06-15 - A live feedback code quality tool for Pharo.
* [Rules](https://github.com/jecisc/Rules) ⭐ 3 | 🐛 4 | 🌐 Smalltalk | 📅 2022-05-16 - Rules is a small model of rules that a model should not violate. It is able to compute the technical debt for a set of violations.

## Command line

* [pi](https://github.com/hernanmd/pi) ⭐ 41 | 🐛 8 | 🌐 Shell | 📅 2026-04-05 - CLI tool to install Pharo Smalltalk packages.
* [clap-st](https://github.com/cdlm/clap-st) ⚠️ Archived - Command-line argument parsing for Pharo.
* [Pharo server tools](https://github.com/svenvc/pharo-server-tools) ⭐ 28 | 🐛 1 | 🌐 Shell | 📅 2023-07-05 - Tools to deploy and manage headless Pharo servers from the command line.
* [Launchpad](https://github.com/ba-st/Launchpad) ⭐ 17 | 🐛 5 | 🌐 Smalltalk | 📅 2026-07-08 - A command-line interface to start, list, and explain the applications available within the image

## Component-Based Architectures

* [Molecule](https://github.com/OpenSmock/Molecule) ⭐ 34 | 🐛 16 | 🌐 Smalltalk | 📅 2026-05-12 - A component oriented framework for Pharo.

## Data interexchange format

* [STON](https://github.com/svenvc/ston) ⭐ 147 | 🐛 3 | 🌐 Smalltalk | 📅 2026-07-14 - The Smalltalk Object Notation, similar to JSON but for Smalltalk.
* [Pillar](https://github.com/pillar-markup/pillar) ⭐ 57 | 🐛 261 | 🌐 Smalltalk | 📅 2026-08-19 - Markup syntax and associated tools to write and generate documentation, books and slides.
* [NeoJSON](https://github.com/svenvc/NeoJSON) ⭐ 47 | 🐛 3 | 🌐 Smalltalk | 📅 2025-09-11 - Framework to handle JSON in Pharo.
* [CSV](https://github.com/svenvc/NeoCSV) ⭐ 36 | 🐛 8 | 🌐 Smalltalk | 📅 2026-06-11 - NeoCSV is an elegant and efficient standalone Smalltalk framework to read and write CSV converting to or from Smalltalk objects.
* [Fuel](https://github.com/theseion/Fuel) ⭐ 31 | 🐛 27 | 🌐 Smalltalk | 📅 2026-07-18 - A general-purpose object serialization framework for Squeak and Pharo, developed in Pharo.
* [msgpack-smalltalk](https://github.com/msgpack/msgpack-smalltalk) ⭐ 23 | 🐛 0 | 🌐 Smalltalk | 📅 2025-05-19 - MessagePack serialization library.
* [SIXX](https://github.com/mumez/SIXX) ⭐ 15 | 🐛 0 | 🌐 Smalltalk | 📅 2025-05-18 - XML serializer/deserializer.
* [Protobuf](https://github.com/jvdsandt/protobuf-smalltalk) ⭐ 14 | 🐛 1 | 🌐 Smalltalk | 📅 2020-03-17 - [Google's protocol buffers](https://developers.google.com/protocol-buffers/) support for Pharo Smalltalk.
* [Tabular](https://github.com/VincentBlondeau/Tabular) ⭐ 14 | 🐛 9 | 🌐 Smalltalk | 📅 2023-10-28 - Support of common spreadsheets formats (CSV, XLSX, ODS).
* [XML-Parser](https://github.com/pharo-contributions/XML-XMLParser) ⭐ 14 | 🐛 3 | 🌐 Smalltalk | 📅 2025-10-26 - Official XML parser maintained by Pharo community.
* [Soup](https://github.com/Ducasse/Soup) ⭐ 7 | 🐛 2 | 🌐 Smalltalk | 📅 2026-06-27 - HTML Scraping library for Pharo.
* [XML-XMLParserHTML](https://github.com/pharo-contributions/XML-XMLParserHTML) ⭐ 6 | 🐛 0 | 🌐 Smalltalk | 📅 2025-01-13 - Official parsers for HTML that convert possibly malformed HTML into well-formed XML maintained by Pharo community.
* [XML-XPath](https://github.com/pharo-contributions/XML-XPath) ⭐ 6 | 🐛 2 | 🌐 Smalltalk | 📅 2024-08-04 - Official XPath library for Pharo.
* [NeoUniversalBinaryJSON](https://github.com/svenvc/NeoUniversalBinaryJSON) ⭐ 5 | 🐛 0 | 🌐 Smalltalk | 📅 2020-06-29 - An implementation of [Universal Binary JSON](http://ubjson.org) (UBJSON) for Pharo.
* [pharo-ical](https://github.com/juliendelplanque/pharo-ical) ⭐ 5 | 🐛 2 | 🌐 Smalltalk | 📅 2019-07-26 - iCalendar import and export.
* [XML-XMLWriter](https://github.com/pharo-contributions/XML-XMLWriter) ⭐ 5 | 🐛 0 | 🌐 Smalltalk | 📅 2024-05-28 - Official XML generation framework maintained by Pharo community.
* [XML-Support](https://github.com/svenvc/XML-Support-Pharo) ⭐ 4 | 🐛 0 | 🌐 Smalltalk | 📅 2019-10-14 - XML Support for Pharo.
* [Arff](https://github.com/juliendelplanque/Arff) ⭐ 1 | 🐛 0 | 🌐 Smalltalk | 📅 2018-04-16 - An Arff generator written in Pharo, Arff is the dataformat used by weka.
* [XML-Pastell](https://github.com/pharo-contributions/XML-Pastell) ⭐ 0 | 🐛 1 | 🌐 Smalltalk | 📅 2019-11-18 - An XPath-like DSL that makes navigation in XML DOM trees easier.
* [XML-XMLParserStAX](https://github.com/pharo-contributions/XML-XMLParserStAX) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2026-07-06 - Official XML pull parser for XMLParser maintained by Pharo community.

## Data Structures

The project <http://github.com/Pharo-containers> contains several data structures. Some more are in nursery in <https://github.com/Ducasse/>.
The general idea is to have a place to be able to find datastructures.

* [DataFrame](https://github.com/PolyMathOrg/DataFrame) ⭐ 79 | 🐛 37 | 🌐 Smalltalk | 📅 2025-02-19 - Tabular data structures for data analysis.
* [Iterators](https://github.com/juliendelplanque/Iterators) ⭐ 9 | 🐛 6 | 🌐 Smalltalk | 📅 2020-05-03 - Implementation of the iterator design pattern.
* [Array2D](https://github.com/pharo-containers/Containers-Array2D) ⭐ 4 | 🐛 2 | 🌐 Smalltalk | 📅 2026-04-16 - A grid like structure.
* [OrderedSet](https://github.com/olekscode/Containers-OrderedSet) ⭐ 4 | 🐛 2 | 🌐 Smalltalk | 📅 2026-03-20 - A Set where an order of elements matters or an OrderedCollection with no duplicates. Supports the complete API of Set and OrderedCollection. Another version or the same is available at <https://github.com/pharo-containers/Containers-OrderedSet> ⭐ 4 | 🐛 2 | 🌐 Smalltalk | 📅 2026-03-20
* [Trie](https://github.com/pharo-containers/Containers-Trie) ⭐ 4 | 🐛 0 | 🌐 Smalltalk | 📅 2026-03-20 - a structure for retrieval information.
* [AVL Tree ](https://github.com/pharo-containers/AVL) ⭐ 3 | 🐛 0 | 🌐 Smalltalk | 📅 2026-03-10
* [Grid](https://github.com/Ducasse/Containers-Grid) ⭐ 3 | 🐛 0 | 🌐 Smalltalk | 📅 2022-09-29 - A grid implementation.
* [Dictionary with lookup](https://github.com/Ducasse/Containers-PropertyEnvironment) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2024-07-21 - A dictionary with lookup.
* [PropertyEnvironment](https://github.com/Ducasse/Containers-PropertyEnvironment) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2024-07-21 - A dictionary of properties with a lookup in ancestors (also called environment in other languages).
* [QuadTrees](https://github.com/Ducasse/QuadTree/) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2022-12-21.
* [UniqueOrdered ](https://github.com//pharo-containers/Containers-UniqueOrdered) ⭐ 2 | 🐛 2 | 🌐 Smalltalk | 📅 2025-04-16 - Some collections to have unique ordered elements.
* [Hastable](https://github.com/pharo-containers/Containers-HashTable) ⭐ 1 | 🐛 1 | 🌐 Smalltalk | 📅 2025-04-16.
* [RunArray](https://github.com/pharo-containers/Containers-RunArray) ⭐ 1 | 🐛 5 | 🌐 Smalltalk | 📅 2021-01-01.
* [SkipList](https://github.com/Ducasse/Containers-SkipList) ⭐ 1 | 🐛 0 | 🌐 Smalltalk | 📅 2019-06-01.
* [BTree](https://github.com/pharo-containers/BTree) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2025-03-26 - Not a binary tree but a BTree implementation.
* [KeyedTree](https://github.com/pharo-containers/Containers-KeyedTree) ⭐ 0 | 🐛 2 | 🌐 Smalltalk | 📅 2026-03-20.
* [Multimap](https://github.com/Ducasse/Containers-OrderedMultiMap) ⭐ 0 | 🐛 3 | 🌐 Smalltalk | 📅 2022-09-03 - A multi map implementation.
* [OrderPreservingDictionary](https://github.com/Ducasse/Containers-OrderPreservingDictionary) ⭐ 0 | 🐛 1 | 🌐 Smalltalk | 📅 2021-01-01 - Order preserving dictionary.
* [Stack](https://github.com/pharo-containers/Containers-Stack) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2026-04-16 - A stack implementation.

## Databases

* [P3](https://github.com/svenvc/P3) ⭐ 81 | 🐛 7 | 🌐 Smalltalk | 📅 2025-11-29 - PostgresV3 protocol client for Pharo, standalone and integrated with Glorp.
* [Soil](https://github.com/ApptiveGrid/Soil) ⭐ 66 | 🐛 40 | 🌐 Smalltalk | 📅 2026-08-18 - Object oriented database library. Persistency to disk with transactions and search indexes.
* [Voyage](https://github.com/pharo-nosql/voyage) ⭐ 36 | 🐛 8 | 🌐 Smalltalk | 📅 2025-10-10 - An object persistence abstraction layer for Pharo.
* [ReStore](https://github.com/rko281/ReStoreForPharo) ⭐ 35 | 🐛 6 | 🌐 Smalltalk | 📅 2026-06-10 - Relational database persistence for Pharo objects (based on SQLite, PostgreSQL or MySQL).
* [Glorp](https://github.com/pharo-rdbms/glorp) ⭐ 28 | 🐛 48 | 🌐 Smalltalk | 📅 2025-07-10 - Multi-database cross-platform object-relational persistence for Pharo and many other Smalltalks.
* [SQLite3](https://github.com/pharo-rdbms/Pharo-SQLite3) ⭐ 23 | 🐛 12 | 🌐 Smalltalk | 📅 2025-07-10 - Community-owned official SQLite3 binding for Pharo. Includes packages for use in Glorp.
* [Simple-Persistence](https://github.com/seandenigris/Simple-Persistence) ⭐ 17 | 🐛 12 | 🌐 Smalltalk | 📅 2026-06-30 - Simple file base persistence for when you don't quite need a database.
* [Tarantalk](https://github.com/mumez/Tarantalk) ⭐ 14 | 🐛 0 | 🌐 Smalltalk | 📅 2022-03-24 - Tarantool client for Pharo.
* [PunQLite](https://github.com/mumez/PunQLite) ⭐ 12 | 🐛 0 | 🌐 Smalltalk | 📅 2026-01-16 - UnQLite binding for Pharo Smalltalk.
* [Garage](https://github.com/pharo-rdbms/garage) ⭐ 11 | 🐛 14 | 🌐 Smalltalk | 📅 2020-01-07 - Database drivers for the Pharo language.
* [pharo-ado](https://github.com/eftomi/pharo-ado) ⭐ 10 | 🐛 11 | 🌐 Smalltalk | 📅 2020-08-27 - Enable data persistence in Pharo by using ActiveX Data Objects (ADO) on Microsoft Windows and external DBMS.
* [SCouchDB](https://github.com/jmari/SCouchDB) ⭐ 8 | 🐛 0 | 🌐 Smalltalk | 📅 2022-10-05 - Pharo driver for CouchDB database using Zinc client. Supports Mango queries and implements Voyage API.
* [Pharo-UDBC](https://github.com/astares/Pharo-UDBC) ⭐ 7 | 🐛 0 | 🌐 Smalltalk | 📅 2020-01-07 - Pharo Universal Database Connectivity.
* [CouchDB](https://github.com/eMaringolo/pharo-couchdb) ⭐ 4 | 🐛 1 | 🌐 Smalltalk | 📅 2019-03-13 - Pharo client for CouchDB NoSQL Document Database.
* [CDB](https://github.com/Ducasse/CDB) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2019-03-14 - a CDB implementation in Pharo.

## Datasets

* [Datasets](https://github.com/pharo-ai/Datasets) ⭐ 10 | 🐛 1 | 🌐 Smalltalk | 📅 2025-09-29 - A collection of small toy datasets used for demonstration and experiments with AI and machine learning. Includes many famous datasets such as Iris, Boston Housing, Wine, Diabetes, MNIST, etc.
* [RandomPartitioner](https://github.com/pharo-ai/RandomPartitioner) ⭐ 6 | 🐛 2 | 🌐 Smalltalk | 📅 2025-09-29 - A tool for partitioning a dataset. Given a set of proportions (e.g. 50%, 30%, and 20%), it shuffles the collection and divides it into non-empty subsets in such a way that every element is included in exactly one subset. Can be used in machine learning and statistical analysis for splitting datasets into training, validation, and test sets.
* [Les Miserables](https://github.com/bergel/LesMiserables) ⭐ 3 | 🐛 0 | 🌐 Smalltalk | 📅 2021-09-14 - Coappearance characters of Les Miserables.

## Deployment

* [Docker Pharo Runtime](https://github.com/ba-st/docker-pharo-runtime) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2026-03-11 - Docker image for Pharo
* [Docker Pharo VM](https://github.com/ba-st/docker-pharo-vm) ⭐ 4 | 🐛 0 | 🌐 Dockerfile | 📅 2026-03-10 - Docker image for Pharo VM

## Documents Generation

* [Artefact](https://github.com/pharo-contributions/Artefact) ⭐ 18 | 🐛 7 | 🌐 Smalltalk | 📅 2024-06-25 - Artefact is a framework to generate PDF documents in Pharo.

## Geography

* [GeoView](https://github.com/ThalesGroup/GeoView) ⭐ 14 | 🐛 17 | 🌐 Smalltalk | 📅 2026-06-10 - Views to display and interact with geographical objects and cartographic layers for UI.
* [PharoOWS](https://github.com/ThalesGroup/PharoOWS) ⭐ 9 | 🐛 2 | 🌐 Smalltalk | 📅 2026-02-08 - OGC Web Services (OWS) support for Pharo.
* [GeoTools](https://github.com/ThalesGroup/GeoTools) ⭐ 6 | 🐛 2 | 🌐 Smalltalk | 📅 2026-01-16 - Geographic Tools as Coordinates, Kinematics and Geodesic utilities for GIS.

## Graphics

* [Bloc](https://github.com/pharo-graphics/Bloc) ⭐ 95 | 🐛 189 | 🌐 Smalltalk | 📅 2026-08-21 - Next generation low-level UI infratructure and framework for Pharo.
* [Pyramid](https://github.com/OpenSmock/Pyramid) ⭐ 45 | 🐛 26 | 🌐 Smalltalk | 📅 2026-07-30 - Pyramid is a Graphical User-Interface (GUI) builder and editor for Bloc and Toplo.
* [Sparta](https://github.com/syrel/Sparta) ⭐ 33 | 🐛 3 | 🌐 Smalltalk | 📅 2026-08-26 - Sparta is an almost stateless vector graphics API for Pharo that provides bindings to the Moz2D rendering backend.
* [Toplo](https://github.com/pharo-graphics/Toplo) ⭐ 31 | 🐛 25 | 🌐 Smalltalk | 📅 2026-08-07 - A widget framework on top of Bloc.
* [Roassal3](https://github.com/pharo-graphics/Roassal) ⭐ 29 | 🐛 24 | 🌐 Smalltalk | 📅 2026-06-30 - The agile 2D visualization engine for Pharo version 3. (V2: [Roassal2](https://github.com/ObjectProfile/Roassal2) ⭐ 28 | 🐛 0 | 🌐 Smalltalk | 📅 2023-04-19)
* [PlantUMLPharoGizmo](https://github.com/fuhrmanator/PlantUMLPharoGizmo) ⭐ 17 | 🐛 7 | 🌐 Smalltalk | 📅 2022-01-23 - Pharo support for PlantUML.
* [Woden](https://github.com/ronsaldo/woden) ⭐ 14 | 🐛 0 | 🌐 Smalltalk | 📅 2024-01-26 - A 3D graphics engine for Pharo.
* [Jun](https://github.com/tomooda/Jun) ⭐ 13 | 🐛 0 | 🌐 Smalltalk | 📅 2024-10-30 - A 3D graphics library with chemoinformatics extensions.
* [Alexandrie](https://github.com/pharo-graphics/Alexandrie) ⭐ 8 | 🐛 23 | 🌐 Smalltalk | 📅 2026-07-28 - FFI bindings and a 2D canvas for Pharo based on Cairo, Freetype and Harfbuzz
* [GraphViz](https://github.com/hernanmd/GraphViz) ⭐ 8 | 🐛 1 | 🌐 Smalltalk | 📅 2024-11-03 - Pharo GraphViz binding.
* [MaterialColors](https://github.com/DuneSt/MaterialColors) ⭐ 3 | 🐛 0 | 🌐 Smalltalk | 📅 2022-05-14 - Project implementing Material Design recommandations on colors.
* [SpecUIAddOns](https://github.com/hernanmd/SpecUIAddOns) ⭐ 3 | 🐛 2 | 🌐 Smalltalk | 📅 2023-02-13 - Add-ons for Spec UI description framework.
* [Bloc-Serialization](https://github.com/OpenSmock/Bloc-Serialization) ⭐ 2 | 🐛 2 | 🌐 Smalltalk | 📅 2026-05-12 - Bloc serialization features to store/unstore BlElements.
* [CSSParser](https://github.com/pharo-contributions/CSSParser) ⭐ 2 | 🐛 3 | 🌐 Smalltalk | 📅 2026-02-11 - A library that provides an object model and tools to read, interpret, and manipulate CSS stylesheets (including .css files).
* [MermaidPharo](https://github.com/badetitou/MermaidPharo) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2023-10-06 - Pharo support for [MermaidJS](https://mermaid.js.org/#/).
* [Stylesheet](https://github.com/pharo-contributions/Stylesheet) ⭐ 2 | 🐛 1 | 🌐 Smalltalk | 📅 2022-02-02 - Stylesheet is a project to define css like stylesheet in Pharo applications.
* [ConstraintsLayout](https://github.com/tesonep/ConstraintsLayout) ⭐ 1 | 🐛 0 | 🌐 Smalltalk | 📅 2018-09-13 - A constraints layout for morphic using Cassowary as its backend.
* [Colors Extensions](https://github.com/pharo-contributions/ColorsExtensions) ⭐ 1 | 🐛 0 | 🌐 Smalltalk | 📅 2023-10-19 - Extensions to Pharo colors.
* [GEXF](https://github.com/badetitou/PharoGEXF) ⭐ 1 | 🐛 0 | 🌐 Smalltalk | 📅 2024-09-18 - Pharo [GEXF file](https://gexf.net/) model and exporter.
* [Toplo-Serialization](https://github.com/OpenSmock/Toplo-Serialization) ⭐ 1 | 🐛 3 | 🌐 Smalltalk | 📅 2026-06-05 - Toplo serialization features to store/unstore ToElements.

## IDE

* [Glamorous Toolkit](https://github.com/feenkcom/gtoolkit) ⭐ 1,558 | 🐛 337 | 🌐 Smalltalk | 📅 2026-08-26 - Moldable IDE for Pharo.
* [Webside](https://github.com/guillermoamaral/Webside) ⭐ 60 | 🐛 30 | 🌐 JavaScript | 📅 2026-02-14 - Web based IDE for Pharo and other Smalltalk systems.
* [Smalltalk Vim Mode](https://github.com/unchartedworks/SmalltalkVimMode) ⭐ 46 | 🐛 4 | 🌐 Smalltalk | 📅 2021-12-18 - Vim Mode for Playground, System Browser, Debugger in Pharo.
* [TelePharo](https://github.com/pharo-ide/TelePharo) ⭐ 45 | 🐛 5 | 🌐 Smalltalk | 📅 2026-08-13 - Tools to manage and develop remote Pharo images.
* [Calypso](https://github.com/pharo-ide/Calypso) ⭐ 41 | 🐛 90 | 🌐 Smalltalk | 📅 2026-08-13 - Pharo system browser.
* [Mirage](https://github.com/juliendelplanque/Mirage) ⭐ 35 | 🐛 4 | 🌐 Smalltalk | 📅 2019-04-18 - A windows switcher with a previewer for Pharo.
* [Uncommon-Themes](https://github.com/David5i6/Uncommon-Themes) ⭐ 16 | 🐛 0 | 🌐 Smalltalk | 📅 2025-01-02 - A collection of themes for Pharo.
* [TilingWindowManager](https://github.com/Pharophile/TilingWindowManager) ⭐ 15 | 🐛 4 | 🌐 Smalltalk | 📅 2022-04-02 - Tiling Window Manager for Pharo.
* [Dawn theme](https://github.com/sebastianconcept/PharoDawnTheme) ⭐ 14 | 🐛 0 | 🌐 Smalltalk | 📅 2024-02-06 - A warm dark theme for Pharo.
* [OpenSmock](https://github.com/OpenSmock/OpenSmock) ⭐ 6 | 🐛 3 | 🌐 Smalltalk | 📅 2026-06-10 -A collection of tools and workshops designed to streamline the development of applications - especially user interfaces (UI).
* [CollectionExtensions](https://github.com/pharo-contributions/CollectionExtensions) ⭐ 3 | 🐛 2 | 🌐 Smalltalk | 📅 2021-12-14 - Extensions for Pharo collections API.
* [Native-Browser](https://github.com/jecisc/Native-Browser) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2019-02-26 - A small project to add the possibility to open native browser via a FileReference.

## Interaction

* [GitBridge](https://github.com/jecisc/GitBridge) ⭐ 18 | 🐛 1 | 🌐 Smalltalk | 📅 2025-03-28 - Access resources and information from the git repository containing your project.
* [OSC](https://github.com/Ducasse/OSC) ⭐ 8 | 🐛 2 | 🌐 Smalltalk | 📅 2025-09-29 - An open sound control library.
* [PharoStreamDeck](https://github.com/OpenSmock/PharoStreamDeck) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-01 - Elgato Stream Deck utils for Pharo.
* [TUIO](https://github.com/Ducasse/TUIO) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2021-05-22 - A driver for TUIO.

## IOT

* [PharoThings](https://github.com/pharo-iot/PharoThings) ⭐ 93 | 🐛 3 | 🌐 Smalltalk | 📅 2026-08-13 - Live programming platform for IoT projects based on Pharo.
* [HID](https://github.com/tamerescrl/libusb-pharo#hid-layer) ⭐ 5 | 🐛 7 | 🌐 Smalltalk | 📅 2018-10-08 - An implementation of the Human Interface Device protocol with a driver to be used with libusb.
* [Netatmo API](https://github.com/labordep/PharoNetatmoAPI) ⭐ 5 | 🐛 0 | 🌐 Smalltalk | 📅 2023-03-17 - Netatmo API implementation for Legrand Netatmo products (Weather Station and Healthy HomeCoach / Aircare product).

## Language extensions

* [Talents](https://github.com/tesonep/pharo-talents) ⭐ 24 | 🐛 8 | 🌐 Smalltalk | 📅 2024-10-28 - Implementation of Talents in Pharo. Allowing us to extend the behaviour in single instances.
* [Buoy](https://github.com/ba-st/Buoy) ⭐ 23 | 🐛 2 | 🌐 Smalltalk | 📅 2026-07-01 - A complement to Pharo
* [I18N](https://github.com/astares/Pharo-I18N) ⭐ 6 | 🐛 0 | 🌐 Smalltalk | 📅 2025-01-20 - Internationalization support for applications.

## LaTeX

* [SmalltalkEnv](https://github.com/mattonem/SmalltalkEnv) ⭐ 8 | 🐛 0 | 🌐 TeX | 📅 2019-09-05 - LaTeX environment for Smalltalk.
* [Citezen](https://github.com/Ducasse/Citezen) ⭐ 5 | 🐛 21 | 🌐 Smalltalk | 📅 2026-03-15 - A bibtext parser and tool suite.

## Loggers

* [TinyLogger](https://github.com/jecisc/TinyLogger) ⭐ 17 | 🐛 6 | 🌐 Smalltalk | 📅 2025-06-20 - A small textual logger for Pharo applications.
* [Bell](https://github.com/ba-st/Bell) ⭐ 7 | 🐛 1 | 🌐 Smalltalk | 📅 2026-06-09 - An observability library written in Smalltalk.
* [SystemLogger](https://github.com/Ducasse/SystemLogger/) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2025-02-14 - An extensible object logger.
* [Toothpick](https://github.com/pdebruic/Toothpick) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2021-08-21 - A textual logger for Pharo.
* [Beacon](https://pharo-project/pharo) - The default object logger of Pharo.

## Meta-modelling

* [Magritte](https://github.com/magritte-metamodel/magritte) ⭐ 70 | 🐛 10 | 🌐 Smalltalk | 📅 2025-04-30 - A fully dynamic meta-description framework.

## Miscellaneous

* [PTerm](https://github.com/lxsang/PTerm) ⭐ 45 | 🐛 10 | 🌐 Smalltalk | 📅 2025-03-08 - Using Unix terminal from Pharo.
* [IPFS](https://github.com/khinsen/ipfs-pharo) ⭐ 25 | 🐛 0 | 🌐 Smalltalk | 📅 2021-12-16 - Binding to InterPlanetary File System for Pharo.
* [Territorial](https://github.com/hernanmd/Territorial) ⭐ 21 | 🐛 1 | 🌐 Smalltalk | 📅 2026-05-25 - Geographical Information Retrieval (GIR) project including features to access geopolitical objects like Nations, Cities, Regions, International Organizations, and statistical data.
* [Fog](https://github.com/smartanvil/Fog) ⭐ 20 | 🐛 1 | 🌐 Smalltalk | 📅 2019-09-12 - Pharo Ethereum Driver.
* [PharoMisc](https://github.com/bouraqadi/PharoMisc) ⭐ 16 | 🐛 0 | 🌐 Smalltalk | 📅 2026-01-08 - Small utilities and libraries around various topics.
* [Aconcagua](https://github.com/ba-st/aconcagua) ⭐ 13 | 🐛 4 | 🌐 Smalltalk | 📅 2026-07-14 - This model represents measures as first class objects, that is, an object that encapsulates a number with its unit.
* [DMirror](https://github.com/ObjectProfile/DMirror) ⭐ 9 | 🐛 0 | 🌐 Smalltalk | 📅 2024-02-01 - Tool to spawn new job on forked Pharo images.
* [Chalten](https://github.com/ba-st/Chalten) ⭐ 8 | 🐛 2 | 🌐 Smalltalk | 📅 2026-07-03 - This is a time model that allows to use dates, months, years, etc. in an easy way.
* [ISO3166](https://github.com/hernanmd/ISO3166) ⭐ 4 | 🐛 0 | 🌐 Smalltalk | 📅 2022-07-07 - Codes for the names of countries, dependent territories, and special areas of geographical interest for Pharo applications.
* [BugReport](https://github.com/jecisc/BugReport) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2022-04-13 - A small project to ease the bug reporting in Pharo application by dumping clear and detailed stacks.
* [Dr Geo](http://www.drgeo.eu/home) - A software to design & manipulate interactive geometric sketches. It helps kids to explore geometry.
* [PharoFamily](https://files.pharo.org/media/pharo-family1.pdf) - PDF image showing a part of Pharo ecosystem.

## Network protocols

* [WebSocket with Zinc](https://github.com/svenvc/zinc) ⭐ 107 | 🐛 29 | 🌐 Smalltalk | 📅 2026-05-11 - The WebSocket feature of the Zinc HTTP Components framework.
* [Stargate](https://github.com/ba-st/Stargate) ⭐ 35 | 🐛 4 | 🌐 Smalltalk | 📅 2026-06-12 - A library supporting the creation of HTTP based RESTful APIs.
* [JRPC](https://github.com/juliendelplanque/JRPC) ⭐ 13 | 🐛 4 | 🌐 Smalltalk | 📅 2026-01-17 - Yet another [JSON-RPC 2.0](https://www.jsonrpc.org/specification) implementation for Pharo Smalltalk.
* [Zodiac](https://github.com/svenvc/zodiac) ⭐ 10 | 🐛 2 | 🌐 Smalltalk | 📅 2025-10-27 (built-in) - Zodiac is an open-source Smalltalk framework implementing TLS/SSL secure as well as regular socket streams.
* [Superluminal](https://github.com/ba-st/Superluminal) ⭐ 9 | 🐛 6 | 🌐 Smalltalk | 📅 2026-06-15 - Building blocks for creating HTTP requests and API clients
* [Ansible](https://github.com/ba-st/Ansible) ⭐ 7 | 🐛 1 | 🌐 Smalltalk | 📅 2026-04-13 - An AMQP client for Pharo
* [PharoZeroMQ](https://github.com/OpenSmock/PharoZeroMQ) ⭐ 5 | 🐛 1 | 🌐 Smalltalk | 📅 2025-01-31 - ZeroMQ (ØMQ, 0MQ or ZMQ) library for Pharo.
* [FileSystemNetwork](http://smalltalkhub.com/#!/~UdoSchneider/FileSystemNetwork) - Adds WebDAV and FTP support to Pharo's FileSystem framework. This allows you to use remote WebDAV and FTP locations with the same (FileSystem) API that's used for disk access.

## Pharo images management

* [Pharo Launcher](https://github.com/pharo-project/pharo-launcher) ⭐ 115 | 🐛 229 | 🌐 Smalltalk | 📅 2026-07-10 - Official tool to manage your pharo images and download new ones.
* [Pharo Install](https://github.com/hernanmd/pi) ⭐ 41 | 🐛 8 | 🌐 Shell | 📅 2026-04-05 - A command-line tool for installing Pharo Smalltalk packages into fresh images.
* [fari.sh](https://github.com/cdlm/fari.sh) ⭐ 14 | 🐛 4 | 🌐 Shell | 📅 2022-01-25 - Fresh, ready-to-hack Pharo images.

## Projects management

* [Filetree](https://github.com/dalehenrich/filetree) ⭐ 133 | 🐛 49 | 🌐 Smalltalk | 📅 2023-11-28 - A file-per-method export format of Pharo source code allowing one to version code with git, svn, fosil, etc.
* [SmalltalkCI](https://github.com/hpi-swa/smalltalkCI) ⭐ 107 | 🐛 82 | 🌐 Smalltalk | 📅 2026-08-26 - Framework for testing Smalltalk projects on Linux, macOS, and Windows and on Travis CI, AppVeyor, and GitLab CI/CD.
* [Metacello](https://github.com/Metacello/metacello) ⭐ 92 | 🐛 129 | 🌐 Smalltalk | 📅 2022-06-03 - A package management system for Pharo.
* [Cruiser](https://github.com/VincentBlondeau/Cruiser) ⭐ 45 | 🐛 7 | 🌐 Smalltalk | 📅 2020-01-20 - Application packager for Pharo.
* [Tonel](https://github.com/pharo-vcs/tonel) ⭐ 33 | 🐛 30 | 🌐 Smalltalk | 📅 2026-07-05 - A file-per-class export format of Pharo source code allowing one to version code with git, svn, fosil, etc.
* [pharo-server-tools](https://github.com/svenvc/pharo-server-tools) ⭐ 28 | 🐛 1 | 🌐 Shell | 📅 2023-07-05 - Tools to deploy and manage headless Pharo servers from the command line.
* [Chrysal](https://github.com/Ducasse/Chrysal) ⭐ 7 | 🐛 1 | 🌐 Smalltalk | 📅 2026-03-25 - How to manage application configuration.
* [DeploymentUtility](https://github.com/jecisc/DeploymentUtility) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2022-06-01 - A project providing a facade to help to deploy pharo projects.

## Scientific libraries

* [Polymath](https://github.com/PolyMathOrg/PolyMath) ⭐ 175 | 🐛 58 | 🌐 Smalltalk | 📅 2026-05-29 - Set of mathematical tools for Pharo. Similar to numpy in Python.
* [Kendrick](https://github.com/UMMISCO/kendrick) ⭐ 53 | 🐛 76 | 🌐 Smalltalk | 📅 2026-03-19 - Domain-Specific Modeling for Epidemiology.
* [CORMAS](https://github.com/cormas/cormas) ⭐ 34 | 🐛 35 | 🌐 Smalltalk | 📅 2026-07-11 - CORMAS (Common-pool Resource and Multi-Agent Simulation) is a agent based model library in Smalltalk.
* [Mathemagics](https://github.com/grpistoia/Mathemagics) ⭐ 26 | 🐛 0 | 🌐 Smalltalk | 📅 2024-02-28 - Symbolic algebra package that handles mathematical expressions using simplification, derivatives, functions, variables, etc. Calculator included. Parser supports infix notation.
* [BioSmalltalk](https://github.com/hernanmd/BioSmalltalk) ⭐ 21 | 🐛 2 | 🌐 Smalltalk | 📅 2026-07-27 - Bioinformatics Library for Pharo Smalltalk.
* [MatplotLibBridge](https://github.com/juliendelplanque/MatplotLibBridge) ⭐ 19 | 🐛 3 | 🌐 Smalltalk | 📅 2019-05-20 - A bridge to Python's Matplotlib.
* [Units](https://github.com/zweidenker/Units) ⭐ 18 | 🐛 6 | 🌐 Smalltalk | 📅 2025-02-12 - A simple package for Units management in Pharo.
* [HoneyGinger](https://github.com/tomooda/HoneyGinger) ⭐ 7 | 🐛 0 | 🌐 Smalltalk | 📅 2025-12-01 - a fluid dynamics simulation engine focused on interactivity and visualization
* [RMapViewer](https://github.com/ReactionMap/RMapViewer) ⭐ 5 | 🐛 3 | 🌐 Smalltalk | 📅 2023-12-25 - A Viewer for chemical reaction maps.
* [Geometry](https://github.com/TelescopeSt/Geometry) ⭐ 4 | 🐛 14 | 🌐 Smalltalk | 📅 2023-11-23 - A library for representing basic geometry elements and doing computations with them.
* [GADM](https://github.com/hernanmd/GADM) ⭐ 1 | 🐛 0 | 🌐 Smalltalk | 📅 2022-03-10 - A browseable GADM world tree for Pharo Smalltalk.
* [Z3950](https://github.com/hernanmd/Z3950) ⭐ 1 | 🐛 0 | 🌐 Smalltalk | 📅 2015-03-11 - ZOOM FFI Client for Z39.50 Protocol.
* [StNER](https://github.com/hernanmd/StNER) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2025-07-20 - Interface to the Stanford Named Entity Recognizer.

## Software / data analysis

* [Moose](https://github.com/moosetechnology/Moose) ⭐ 156 | 🐛 16 | 🌐 Smalltalk | 📅 2026-08-07 - Platform for software and data analysis.
* [PetitParser](https://github.com/moosetechnology/PetitParser) ⭐ 44 | 🐛 12 | 🌐 Smalltalk | 📅 2021-06-08 - Petit Parser is a framework for building parsers using objects.
* [Gitminer](https://github.com/USIREVEAL/gitminer) ⭐ 11 | 🐛 0 | 🌐 Smalltalk | 📅 2025-06-12 - A tool to mine Git-based software repositories.
* [PostgreSQLParser](https://github.com/juliendelplanque/PostgreSQLParser) ⭐ 7 | 🐛 20 | 🌐 Smalltalk | 📅 2021-03-18 - A parser for PostgreSQL queries and Plpg/SQL source code.
* [CCBC](https://github.com/hernanmd/ccbc) ⭐ 4 | 🐛 0 | 🌐 Smalltalk | 📅 2021-04-20 - Code Critics Bar Chart for Pharo Smalltalk.
* [DesignInfo](https://github.com/hernanmd/DesignInfo) ⭐ 4 | 🐛 1 | 🌐 Smalltalk | 📅 2018-10-25 - Collects package metrics (SLOC).

## Sound

* [Pharo-LibVLC](https://github.com/badetitou/Pharo-LibVLC) ⭐ 16 | 🐛 2 | 🌐 Smalltalk | 📅 2023-09-13 - FFI binding to [libVLC](https://www.videolan.org/developers/vlc/doc/doxygen/html/group__libvlc.html).
* [PharoSound](https://github.com/psvensson/PharoSound) ⭐ 2 | 🐛 1 | 🌐 Smalltalk | 📅 2020-02-09 - Sound facilities for Pharo.

## System interaction

* [OSSubprocess](https://github.com/pharo-contributions/OSSubprocess) ⭐ 37 | 🐛 27 | 🌐 Smalltalk | 📅 2025-12-19 - Allows one to spawn Operating System processes from within Pharo language.
* [PythonBridge](https://github.com/ObjectProfile/PythonBridge) ⭐ 22 | 🐛 8 | 🌐 Smalltalk | 📅 2023-02-08 - A bridge between Python and Pharo. This bridge allows to seamlessly use Python libraries in Pharo
* [Pharo-OS-Windows](https://github.com/astares/Pharo-OS-Windows) ⭐ 14 | 🐛 3 | 🌐 Smalltalk | 📅 2025-07-16 - Support for Windows operating system for Pharo.
* [KerasBridge](https://github.com/ObjectProfile/KerasBridge) ⭐ 6 | 🐛 3 | 🌐 Smalltalk | 📅 2019-12-11 - Bridge between the Keras library for neural network and Pharo
* [LibUSB](https://github.com/tamerescrl/libusb-pharo) ⭐ 5 | 🐛 7 | 🌐 Smalltalk | 📅 2018-10-08 - A FFI binding to libusb C library.
* [Pharo-OS-Linux-Ubuntu](https://github.com/astares/Pharo-OS-Linux-Ubuntu) ⭐ 5 | 🐛 0 | 🌐 Smalltalk | 📅 2023-08-21 - Support for Ubuntu operating system for Pharo.
* [SystemInteraction](https://github.com/jecisc/SystemInteraction) ⭐ 5 | 🐛 1 | 🌐 Smalltalk | 📅 2022-07-11 - A project to simplify system interactions in Pharo providing a facade to OSSubProcess and OSWindSubProcess and some pre-made commands.
* [Pharo-OS-OSX](https://github.com/astares/Pharo-OS-OSX) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2023-08-21 - Support for OSX operating system for Pharo.
* [Pharo-OS-Unix](https://github.com/astares/Pharo-OS-Unix) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2023-08-21 - Support for Unix operating system for Pharo.
* [ProcessWrapper](https://github.com/hernanmd/ProcessWrapper) ⭐ 1 | 🐛 1 | 🌐 Smalltalk | 📅 2019-02-06 - Plugin + Wrapper code for Windows process execution.
* [Pharo-OS-Raspbian](https://github.com/astares/Pharo-OS-Raspbian) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2023-08-21 - Support for Raspbian operating system for Pharo.

## Testing

* [µ-talk](https://github.com/pavel-krivanek/mutalk) ⭐ 25 | 🐛 7 | 🌐 Smalltalk | 📅 2026-04-13 - Mutation Testing in Smalltalk.
* [Mocketry](https://github.com/dionisiydk/Mocketry) ⭐ 18 | 🐛 2 | 🌐 Smalltalk | 📅 2025-06-12 - Mock objects library with very fluent lightweight API.
* [DrTests](https://github.com/juliendelplanque/DrTests/) ⭐ 7 | 🐛 69 | 🌐 Smalltalk | 📅 2019-09-23 - An extendable, plugins-based UI for testing Pharo projects.
* [Hapao](https://github.com/ObjectProfile/Spy2) ⭐ 7 | 🐛 1 | 🌐 Smalltalk | 📅 2021-05-17 - Spy2 is a profiling framework. Spy2 contains Hapao, the visual test coverage tool.
* [StateSpecs](https://github.com/dionisiydk/StateSpecs) ⭐ 7 | 🐛 9 | 🌐 Smalltalk | 📅 2026-08-03 - Assertions library based on should expressions.
* [ParametrizedTests](https://github.com/tesonep/ParametrizedTests) ⭐ 5 | 🐛 1 | 🌐 Smalltalk | 📅 2025-10-06 - Extension to SUnit to implement parametrized tests in Pharo.
* [ShellStone](https://github.com/tomas-stefano/shellstone) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2026-02-04 - RSpec-inspired BDD testing framework with matchers, hooks, and test doubles. Cross-platform (GNU Smalltalk & Pharo). **Experimental**.
* [Babymock](https://github.com/zeroflag/BabyMock) ⭐ 1 | 🐛 0 | 📅 2025-01-14 - A visual mock object library.

## Tutorials

* [Exercism Pharo Smalltalk](https://github.com/exercism/pharo-smalltalk) ⭐ 35 | 🐛 54 | 🌐 Smalltalk | 📅 2026-08-24 - Solve problems with TDD at [Exercism.io](https://exercism.io/) and receive mentor feedback.

## VCS

* [Iceberg](https://github.com/pharo-vcs/iceberg) ⭐ 140 | 🐛 355 | 🌐 Smalltalk | 📅 2026-08-13 - Set of tools to handle git repositories from a Pharo image.

## Videos

* [Infecting morph by virus](https://www.youtube.com/watch?v=mnu51GDhOL4) - Example of usage of [Ghost](https://github.com/pharo-ide/Ghost) ⭐ 3 | 🐛 1 | 🌐 Smalltalk | 📅 2026-08-13 to infect a Morph, making it change the color of other Morphs it touches.
* [How to setup a Pharo project](https://www.youtube.com/watch?v=Wnt3OBhR18I) - Video showing how to setup a Pharo project (continuous-integration setup included).
* [Pharo Tech Talk Feb 2017 : Reflectivity](https://www.youtube.com/watch?v=H52MAu_ISgU) - Reflectivity in Pharo6.
* [Pharo Techtalk: Consortium/Association 2017](https://www.youtube.com/watch?v=jYtNinyj69I) - Live stream for the pharo tech talk March 2018.
* [Pharo TechTalk July 2019: Contribute to Pharo](https://www.youtube.com/watch?v=90T0OSb_Fuo) - TechTalk showing how to contribute to Pharo.

## Virtual Machine

* [Polyphemus](https://github.com/pharo-vcs/iceberg) ⭐ 140 | 🐛 355 | 🌐 Smalltalk | 📅 2026-08-13 - Framework allowing to analyse/query/modify Pharo images without executing them.

## Web

* [Seaside](https://github.com/SeasideSt/Seaside) ⭐ 561 | 🐛 156 | 🌐 Smalltalk | 📅 2026-08-08 - Framework to develop sophisticate web applications in Smalltalk.
* [PharoJS](https://github.com/PharoJS/PharoJS) ⭐ 129 | 🐛 40 | 🌐 JavaScript | 📅 2025-11-05 - Develop in Pharo, Run on Javascript.
* [Zinc](https://github.com/svenvc/zinc) ⭐ 107 | 🐛 29 | 🌐 Smalltalk | 📅 2026-05-11 - HTTP components to deal with HTTP networking in Smalltalk.
* [Teapot](https://github.com/zeroflag/Teapot) ⭐ 104 | 🐛 5 | 🌐 Smalltalk | 📅 2026-05-08 - Micro web framework for Pharo Smalltalk.
* [CodeParadise](https://github.com/ErikOnBike/CodeParadise) ⭐ 97 | 🐛 0 | 🌐 Smalltalk | 📅 2026-08-19 - Run Pharo code inside a tiny SqueakJS VM and manipulate the Dom via WebComponents and MVP
* [Willow](https://github.com/ba-st/Willow) ⭐ 51 | 🐛 4 | 🌐 Smalltalk | 📅 2026-02-11 - Web Interaction Library that eases the burden of creating AJAX-based web applications.
* [MaterialDesignLite](https://github.com/DuneSt/MaterialDesignLite) ⭐ 43 | 🐛 50 | 🌐 Smalltalk | 📅 2026-08-26 - Binding google's Material Design Lite project for Seaside.
* [Parasol](https://github.com/SeasideSt/Parasol) ⭐ 32 | 🐛 15 | 🌐 Smalltalk | 📅 2025-10-16 - Testing web apps in Smalltalk using Selenium WebDriver.
* [OpenAPI](https://github.com/zweidenker/OpenAPI) ⭐ 23 | 🐛 4 | 🌐 Smalltalk | 📅 2026-08-05 - A pharo implementation of [OpenAPI](https://www.openapis.org) 3.0.1, a machine-readable interface files specification for describing, producing, consuming, and visualizing RESTful web services.
* [Ethel](https://github.com/grype/Ethel) ⭐ 22 | 🐛 0 | 🌐 Smalltalk | 📅 2024-06-11 - Lightweight framework for composing web service clients.
* [RenoirSt](https://github.com/ba-st/RenoirSt) ⭐ 18 | 🐛 3 | 🌐 Smalltalk | 📅 2026-01-14 - A DSL enabling programmatic cascading style sheet generation for Pharo Smalltalk.
* [HighchartsSt](https://github.com/ba-st/HighchartsSt) ⭐ 13 | 🐛 6 | 🌐 Smalltalk | 📅 2020-10-07 - A Highcharts Js API wrapper for Pharo Smalltalk.
* [SeasideBootstrap](https://github.com/astares/Seaside-Bootstrap) ⭐ 11 | 🐛 0 | 🌐 Smalltalk | 📅 2023-03-22 - Binding to Twitter's Bootstrap project for Seaside.
* [TelescopeCytoscape](https://github.com/TelescopeSt/TelescopeCytoscape) ⭐ 9 | 🐛 18 | 🌐 Smalltalk | 📅 2022-07-07 - Interactive visualization project for Seaside based on Cytoscape.js.
* [ChartJs](https://github.com/DuneSt/ChartJs) ⭐ 8 | 🐛 4 | 🌐 Smalltalk | 📅 2022-05-14 - Seaside binding of ChartJs to display and interact with charts.
* [Pragma-Validators](https://github.com/radekbusa/Pragma-Validators) ⭐ 3 | 🐛 0 | 🌐 Smalltalk | 📅 2020-11-22 - Pragma validators for Pharo accessors, inspired by Java Bean Validation annotations.
* [PrismCodeDisplayer](https://github.com/DuneSt/PrismCodeDisplayer) ⭐ 2 | 🐛 1 | 🌐 StringTemplate | 📅 2022-05-14 - Code displayer for Seaside base on Prism.js project.
* [Teapot-ACL](https://github.com/radekbusa/Teapot-ACL) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2020-11-22 - A minimalistic role-based access control list for Teapot authorization.
* [WebST](https://github.com/bouraqadi/WebST/) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2025-07-12 - A framework for building Web Components using PharoJS
* [Amber](https://amber-lang.net) - Amber is an implementation of the Smalltalk language that runs on top of the JavaScript runtime. It uses Pharo as reference implementation.

## Web API clients

* [DiscordSt](https://github.com/JurajKubelka/DiscordSt) ⭐ 32 | 🐛 0 | 🌐 Smalltalk | 📅 2022-03-07 - DiscordSt is a client for Discord written in Pharo.
* [Jira-Pharo-API](https://github.com/Evref-BL/Jira-Pharo-API) ⭐ 2 | 🐛 0 | 🌐 Smalltalk | 📅 2026-03-30 - Jira-Pharo-API is a client for [Jira](https://www.atlassian.com/software/jira) written in Pharo.
* [Elasticsearch-Pharo-API](https://github.com/Evref-BL/Elasticsearch-Pharo-API) ⭐ 0 | 🐛 0 | 🌐 Smalltalk | 📅 2023-09-16 - Elasticsearch-Pharo-API is a client for [Elasticsearch](https://www.elastic.co/elasticsearch/) written in Pharo.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._
