# randomwalk

# Dataset Used:
<a href="http://snap.stanford.edu/data/ego-Facebook.html">facebook ego network</a>

# DataStructures Used:
<p><b>adj_list :</b> Adjacancy List (Python List of Lists) to store Network (graph).</p>
<p><b>gender_list :</b> Table (Python List) to store gender of each user in the network.</p>
<p><b>gender_wise_neighbour_indices :</b> Table (Python List of index-list-pair) to store list of indices (in adj_list) of male
neighbours and list of indices of female neighbours for each node.</p>
<p><b>gender_dist:</b> Table (Python Dict) to store number of male and female neighbours of each node. (not required)</p>

# Functions defined:
<p><b>fillupmat:</b>
