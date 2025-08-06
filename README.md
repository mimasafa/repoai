# Presidential Campaign 2024 - Social Media Analysis

Comprehensive big data analysis of social media data (X/Twitter) for the Indonesian Presidential Campaign 2024, following Satria Data 2024 technical guidelines.

## 🎯 Project Overview

This project provides advanced analytics capabilities for understanding campaign dynamics through social media data, including:

- **Complex Network Analysis**: Social interaction patterns and influencer identification
- **Topic Clustering**: Content categorization and trend analysis
- **Polarization Analysis**: Political sentiment and echo chamber detection
- **Advanced Analytics**: Temporal patterns, geographic distribution, and bot detection

## 📊 Dataset

- **File**: `sampel_data_semifinal_satria_data_2024.xlsx - Sheet1.csv`
- **Size**: ~50,000 tweets
- **Columns**:
  - `created_at`: Tweet timestamp
  - `tcode`: Interaction type (rt, mention, reply)
  - `num_retweets`: Retweet count
  - `type`: Content type
  - `frn_cnt`, `flw_cnt`, `sts_cnt`: User metrics
  - `loc`: Location
  - `content`: Tweet content
  - `lang`: Language

## 🚀 Quick Start

### Prerequisites

```bash
pip install -r requirements.txt
```

### Running the Analysis

1. **Open Jupyter Notebook**:
   ```bash
   jupyter notebook presidential_campaign_analysis_2024.ipynb
   ```

2. **Run All Cells**: Execute the notebook from top to bottom for complete analysis

3. **View Results**: Interactive visualizations and reports will be generated automatically

## 📋 Analysis Components

### 1. Data Preprocessing & EDA
- Text cleaning for Indonesian language
- Missing value handling
- Statistical overview and data quality assessment

### 2. Network Analysis
- **Graph Construction**: User interaction networks
- **Centrality Measures**: Degree, betweenness, closeness centrality
- **Community Detection**: Louvain algorithm for community identification
- **Influencer Identification**: Key opinion leaders and network hubs

### 3. Topic Modeling
- **Text Preprocessing**: Stopword removal, stemming (Indonesian)
- **TF-IDF Analysis**: Term frequency-inverse document frequency
- **LDA Implementation**: Latent Dirichlet Allocation for topic discovery
- **Candidate-specific Topics**: Topic distribution per presidential candidate

### 4. Sentiment Analysis
- **Polarity Scoring**: Positive/negative/neutral classification
- **Candidate Sentiment**: Sentiment analysis per presidential candidate
- **Temporal Trends**: Sentiment evolution over time

### 5. Advanced Analytics
- **Temporal Analysis**: Peak activity patterns and timing insights
- **Geographic Distribution**: Location-based analysis
- **Engagement Patterns**: Viral content and user behavior analysis
- **Bot Detection**: Automated account identification

## 🛠️ Technical Stack

- **Data Processing**: pandas, numpy
- **Network Analysis**: networkx, community, igraph
- **NLP**: nltk, spacy, gensim, transformers, BERTopic
- **Indonesian Language**: Sastrawi (stemming, stopwords)
- **Machine Learning**: scikit-learn, LDA
- **Visualization**: matplotlib, seaborn, plotly, bokeh
- **Performance**: dask, joblib

## 📈 Key Features

### Interactive Visualizations
- Network graphs with community coloring
- Topic evolution timelines
- Sentiment trend analysis
- Geographic heatmaps
- Engagement pattern dashboards

### Performance Optimized
- Efficient data processing for large datasets
- Sampling strategies for computationally intensive operations
- Memory-efficient algorithms
- Progress tracking with tqdm

### Comprehensive Reporting
- Executive summary with key findings
- Actionable insights for stakeholders
- Methodology documentation
- Reproducible analysis pipeline

## 🎯 Use Cases

### Campaign Teams
- Monitor public sentiment in real-time
- Identify key influencers for engagement
- Track topic trends and viral content
- Optimize posting times and strategies

### Media Organizations
- Detect emerging narratives
- Monitor information spread patterns
- Identify polarization and echo chambers
- Verify trending topics authenticity

### Researchers
- Study political communication patterns
- Analyze social network structures
- Investigate misinformation spread
- Understand voter behavior online

## 📊 Sample Outputs

### Network Analysis
- Community structure visualization
- Influencer ranking and metrics
- Interaction flow patterns

### Topic Analysis
- Topic-word distributions
- Candidate-specific topic preferences
- Topic evolution over time

### Sentiment Insights
- Overall sentiment distribution
- Candidate sentiment comparison
- Geographic sentiment mapping

## 🔧 Configuration

### Performance Tuning
- Adjust `sample_size` for network analysis (default: 5,000)
- Modify `max_features` for TF-IDF (default: 1,000)
- Set `n_topics` for LDA modeling (default: 8)

### Customization
- Add custom stopwords in text preprocessing
- Modify candidate keywords for detection
- Adjust sentiment thresholds
- Configure bot detection parameters

## 📚 Documentation

### Notebook Structure
1. **Setup & Imports**: Library initialization and configuration
2. **Data Loading**: Dataset import and initial exploration
3. **Preprocessing**: Data cleaning and text processing
4. **EDA**: Exploratory data analysis and visualization
5. **Network Analysis**: Social network construction and analysis
6. **Topic Modeling**: Content categorization and clustering
7. **Sentiment Analysis**: Emotion and opinion mining
8. **Advanced Analytics**: Temporal, geographic, and behavioral analysis
9. **Executive Summary**: Key findings and recommendations

### Code Organization
- Modular function design for reusability
- Comprehensive error handling
- Performance monitoring and optimization
- Clear documentation and comments

## 🚀 Future Enhancements

1. **Real-time Processing**: Stream processing for live analysis
2. **Advanced NLP**: Integration with BERT/GPT models
3. **Cross-platform Analysis**: Instagram, TikTok, YouTube integration
4. **Predictive Modeling**: Viral content and trend forecasting
5. **Interactive Dashboard**: Web-based monitoring interface

## 📝 Contributing

This project is designed for educational and research purposes. Contributions are welcome for:
- Performance improvements
- Additional analysis methods
- Enhanced visualizations
- Documentation updates

## 📄 License

This project is part of the Satria Data 2024 competition and follows academic research guidelines.

## 📞 Contact

For technical questions or collaboration opportunities, please reach out through the repository issues or discussions.

---

**© 2024 Presidential Campaign Social Media Analysis Project**