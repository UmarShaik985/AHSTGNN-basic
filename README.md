# GNN-Basic
**GNN ( Graph Neural Network )**<br>
graph neural network is a Ai-model which works on Graphical structured data.
<br>

**Graph :**
<br>
A graph contains Nodes and Edges.
<br>
Node: repersents an object or entity.
<br>
Edges: represents connection between Nodes.
<br>

**example :**
<br>
A -- B<br>
|<br>
|<br>
C<br>

**Applications :**
<br>
1.fraud detection.<br>
2.social networks.<br>
3.traffic detection.<br>
4.recommendation system.<br>
5.molecular Analysis.<br>

# AHSTGNN-Basic
**AHSTGNN - Adaptive Hybrid Spatial Temporal Graph Neural Network : **
<br>

It's used for cellular Traffic prediction.
<br>
The main goal is to predict mobile network traffic using both 
<br>
    >> Temporal pattern (network traffic history).
<br>
    >> Spatial pattern (relationship with towers).
<br>

**Main Modules : **
<br>
**TCM ( Temporal Convolution Module ) : **
<br>
Learns traffic patterns over time
<br>
**AHGLM ( Adaptive Hybrid Graph Learning Module ) :**
<br>
Learns both static and dynamic graph relationships.
<br>
**STAM ( Spatial - temporal Adaptive Module ) :**
<br>
combines spatial and temporal information adaptively.
<br>

**Applications :**
  >> Cellular Traffic Prediction.<br>
  >> Smart Cities.<br>
  >> Transportation Systems.<br>
  >> IoT Networks.<br>
  >> Network Resource Management.<br>

# Temporal-Graph-Neural-Network
**TGNN : **
<br>
Temporal graph neural network is a graph neural network which changes over time.

**Example : **
AT 9:00AM 
A -> B

AT 10:00AM
A -> B
B -> C

# commands
**Clone repository : **<br>
git clone <Link><br>

**Install requirement :**
pip install -r requirements.txt

**Generate Training Data : **
python generate_Training_data.py

**Train Model :**
python train.py --gcn_bool --adjtype doubletransition --addaptadj --randomadj

**Test Model : **
python test.py
