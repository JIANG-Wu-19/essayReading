# Zone-Enhanced Spatio-Temporal Representation Learning for Urban POI Recommendation

[Zone-Enhanced Spatio-Temporal Representation Learning for Urban POI Recommendation | IEEE Journals & Magazine | IEEE Xplore](https://ieeexplore.ieee.org/document/10040753)

> ToP achieves ***state-of the-art*** performance in terms of common metrics and provides more insights for consumers' POI check-in actions

* 搞清楚ToP模型的机理

## existing POI recommender systems

learn fixed latent vectors to represent both consumers and POIs from **historical check-ins** and make recommendations **under the spatio-temporal constraints**

从历史签入中学习固定的潜在向量来表示消费者和poi，并在时空约束下提出建议

存在问题：

the challenges of explaining consumers' complicated check-in actions

解释消费者复杂的签到行为的挑战

1. interpretability

   > To enhance the performance of the POI recommendation, the interpretability of the model should be taken into consideration.

   论点：可解释性能够增强POI recommendation的表现

2. Dynamic POI representation

   > a time-dependent representation of POI will be more meaningful and explainable for recommendations

3. Zone effect

   > how to define the suitable zone area to learn a reasonable zone representation for enhancing POI recommendation is a more challenging problem

## 研究成果

1. explore the limitations of POI representations, and address POI recommendation issues with knowledge graph embedding

2. explore the interpretability of recommendations from the POI aspect

3. propose a Time-zone-space POI embedding model(ToP) that use zone's embedding to enhance POI embedding

   > ToP,which integrates ***multi-knowledge graphs*** and ***topic model*** to introduce not only **spatio-temporal effects** but also **sentiment constraints** into POI embeddings for strengthening interpretability of recommendation.
   >
   > ToP learns **multiple latent vectors** for a POI **in a different period** with **spatial constraints** via knowledge graph learning
   >
   > To add sentiment constraints, ToP jointly **combines these vectors with the zone’s representations learned by topic models** to make explainable recommendations.
   >
   > ToP considers the time, space, and sentiment of POI in a **unified embedding framework**, which benefits the POI recommendations

4. propose a structural RotatE

5. evaluate ToP on the Changchun city dataset

## POI recommendations的影响因素

1. users' personal preferences
2. POIs' functions
3. other real world spatio-temporal factors

## ToP

* a spatio-temporal knowledge graph embedding

* a Topic Zone Embedding component
* a unified knowledge graph-based recommendation model



