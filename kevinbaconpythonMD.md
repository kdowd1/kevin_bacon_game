```python
pip install -Iv networkx==1.10
```

    Using pip 22.0.4 from /cvmfs/sft.cern.ch/lcg/views/LCG_102swan/x86_64-centos7-gcc8-opt/lib/python3.9/site-packages/pip (python 3.9)
    Defaulting to user installation because normal site-packages is not writeable
    Collecting networkx==1.10
      Downloading networkx-1.10.zip (1.5 MB)
    [2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m1.5/1.5 MB[0m [31m13.2 MB/s[0m eta [36m0:00:00[0m00:01[0m
    [?25h  Running command python setup.py egg_info
      running egg_info
      creating /tmp/pip-pip-egg-info-751k6q3v/networkx.egg-info
      writing /tmp/pip-pip-egg-info-751k6q3v/networkx.egg-info/PKG-INFO
      writing dependency_links to /tmp/pip-pip-egg-info-751k6q3v/networkx.egg-info/dependency_links.txt
      writing requirements to /tmp/pip-pip-egg-info-751k6q3v/networkx.egg-info/requires.txt
      writing top-level names to /tmp/pip-pip-egg-info-751k6q3v/networkx.egg-info/top_level.txt
      writing manifest file '/tmp/pip-pip-egg-info-751k6q3v/networkx.egg-info/SOURCES.txt'
      listing git files failed - pretending there aren't any
      reading manifest file '/tmp/pip-pip-egg-info-751k6q3v/networkx.egg-info/SOURCES.txt'
      reading manifest template 'MANIFEST.in'
      warning: no files found matching 'scripts/*'
      warning: no files found matching 'networkx/tests/*.txt'
      warning: no files found matching 'networkx/*/*/tests/*.txt'
      warning: no previously-included files matching '*~' found anywhere in distribution
      warning: no previously-included files matching '*.pyc' found anywhere in distribution
      warning: no previously-included files matching '.svn' found anywhere in distribution
      no previously-included directories found matching 'doc/build'
      no previously-included directories found matching 'doc/source/reference/generated'
      no previously-included directories found matching 'doc/source/examples'
      no previously-included directories found matching 'doc/source/static/examples'
      no previously-included directories found matching 'doc/source/templates/gallery.html'
      adding license file 'LICENSE.txt'
      writing manifest file '/tmp/pip-pip-egg-info-751k6q3v/networkx.egg-info/SOURCES.txt'
      Preparing metadata (setup.py) ... [?25l[?25hdone
    Collecting decorator>=3.4.0
      Downloading decorator-5.1.1-py3-none-any.whl (9.1 kB)
    Building wheels for collected packages: networkx
      Running command python setup.py bdist_wheel
      running bdist_wheel
      The [wheel] section is deprecated. Use [bdist_wheel] instead.
      running build
      running build_py
      creating build
      creating build/lib
      creating build/lib/networkx
      copying networkx/version.py -> build/lib/networkx
      copying networkx/exception.py -> build/lib/networkx
      copying networkx/__init__.py -> build/lib/networkx
      copying networkx/convert_matrix.py -> build/lib/networkx
      copying networkx/relabel.py -> build/lib/networkx
      copying networkx/convert.py -> build/lib/networkx
      copying networkx/release.py -> build/lib/networkx
      creating build/lib/networkx/algorithms
      copying networkx/algorithms/swap.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/hybrid.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/isolate.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/__init__.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/cycles.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/link_prediction.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/mis.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/dag.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/distance_measures.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/dominating.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/clique.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/minors.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/boundary.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/mst.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/dominance.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/vitality.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/block.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/richclub.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/distance_regular.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/core.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/graphical.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/hierarchy.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/smetric.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/matching.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/triads.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/simple_paths.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/euler.py -> build/lib/networkx/algorithms
      copying networkx/algorithms/cluster.py -> build/lib/networkx/algorithms
      creating build/lib/networkx/algorithms/assortativity
      copying networkx/algorithms/assortativity/correlation.py -> build/lib/networkx/algorithms/assortativity
      copying networkx/algorithms/assortativity/neighbor_degree.py -> build/lib/networkx/algorithms/assortativity
      copying networkx/algorithms/assortativity/__init__.py -> build/lib/networkx/algorithms/assortativity
      copying networkx/algorithms/assortativity/connectivity.py -> build/lib/networkx/algorithms/assortativity
      copying networkx/algorithms/assortativity/pairs.py -> build/lib/networkx/algorithms/assortativity
      copying networkx/algorithms/assortativity/mixing.py -> build/lib/networkx/algorithms/assortativity
      creating build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/generators.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/__init__.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/matrix.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/spectral.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/redundancy.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/centrality.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/basic.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/projection.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/matching.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/edgelist.py -> build/lib/networkx/algorithms/bipartite
      copying networkx/algorithms/bipartite/cluster.py -> build/lib/networkx/algorithms/bipartite
      creating build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/flow_matrix.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/eigenvector.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/__init__.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/current_flow_betweenness.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/betweenness.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/katz.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/load.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/degree_alg.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/current_flow_closeness.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/betweenness_subset.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/closeness.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/harmonic.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/communicability_alg.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/current_flow_betweenness_subset.py -> build/lib/networkx/algorithms/centrality
      copying networkx/algorithms/centrality/dispersion.py -> build/lib/networkx/algorithms/centrality
      creating build/lib/networkx/algorithms/chordal
      copying networkx/algorithms/chordal/__init__.py -> build/lib/networkx/algorithms/chordal
      copying networkx/algorithms/chordal/chordal_alg.py -> build/lib/networkx/algorithms/chordal
      creating build/lib/networkx/algorithms/community
      copying networkx/algorithms/community/__init__.py -> build/lib/networkx/algorithms/community
      copying networkx/algorithms/community/kclique.py -> build/lib/networkx/algorithms/community
      creating build/lib/networkx/algorithms/components
      copying networkx/algorithms/components/__init__.py -> build/lib/networkx/algorithms/components
      copying networkx/algorithms/components/strongly_connected.py -> build/lib/networkx/algorithms/components
      copying networkx/algorithms/components/biconnected.py -> build/lib/networkx/algorithms/components
      copying networkx/algorithms/components/connected.py -> build/lib/networkx/algorithms/components
      copying networkx/algorithms/components/weakly_connected.py -> build/lib/networkx/algorithms/components
      copying networkx/algorithms/components/semiconnected.py -> build/lib/networkx/algorithms/components
      copying networkx/algorithms/components/attracting.py -> build/lib/networkx/algorithms/components
      creating build/lib/networkx/algorithms/connectivity
      copying networkx/algorithms/connectivity/kcomponents.py -> build/lib/networkx/algorithms/connectivity
      copying networkx/algorithms/connectivity/__init__.py -> build/lib/networkx/algorithms/connectivity
      copying networkx/algorithms/connectivity/cuts.py -> build/lib/networkx/algorithms/connectivity
      copying networkx/algorithms/connectivity/stoerwagner.py -> build/lib/networkx/algorithms/connectivity
      copying networkx/algorithms/connectivity/kcutsets.py -> build/lib/networkx/algorithms/connectivity
      copying networkx/algorithms/connectivity/connectivity.py -> build/lib/networkx/algorithms/connectivity
      copying networkx/algorithms/connectivity/utils.py -> build/lib/networkx/algorithms/connectivity
      creating build/lib/networkx/algorithms/coloring
      copying networkx/algorithms/coloring/__init__.py -> build/lib/networkx/algorithms/coloring
      copying networkx/algorithms/coloring/greedy_coloring.py -> build/lib/networkx/algorithms/coloring
      copying networkx/algorithms/coloring/greedy_coloring_with_interchange.py -> build/lib/networkx/algorithms/coloring
      creating build/lib/networkx/algorithms/flow
      copying networkx/algorithms/flow/networksimplex.py -> build/lib/networkx/algorithms/flow
      copying networkx/algorithms/flow/edmondskarp.py -> build/lib/networkx/algorithms/flow
      copying networkx/algorithms/flow/__init__.py -> build/lib/networkx/algorithms/flow
      copying networkx/algorithms/flow/shortestaugmentingpath.py -> build/lib/networkx/algorithms/flow
      copying networkx/algorithms/flow/maxflow.py -> build/lib/networkx/algorithms/flow
      copying networkx/algorithms/flow/capacityscaling.py -> build/lib/networkx/algorithms/flow
      copying networkx/algorithms/flow/mincost.py -> build/lib/networkx/algorithms/flow
      copying networkx/algorithms/flow/utils.py -> build/lib/networkx/algorithms/flow
      copying networkx/algorithms/flow/preflowpush.py -> build/lib/networkx/algorithms/flow
      creating build/lib/networkx/algorithms/traversal
      copying networkx/algorithms/traversal/__init__.py -> build/lib/networkx/algorithms/traversal
      copying networkx/algorithms/traversal/breadth_first_search.py -> build/lib/networkx/algorithms/traversal
      copying networkx/algorithms/traversal/depth_first_search.py -> build/lib/networkx/algorithms/traversal
      copying networkx/algorithms/traversal/edgedfs.py -> build/lib/networkx/algorithms/traversal
      creating build/lib/networkx/algorithms/isomorphism
      copying networkx/algorithms/isomorphism/__init__.py -> build/lib/networkx/algorithms/isomorphism
      copying networkx/algorithms/isomorphism/isomorphvf2.py -> build/lib/networkx/algorithms/isomorphism
      copying networkx/algorithms/isomorphism/vf2userfunc.py -> build/lib/networkx/algorithms/isomorphism
      copying networkx/algorithms/isomorphism/matchhelpers.py -> build/lib/networkx/algorithms/isomorphism
      copying networkx/algorithms/isomorphism/isomorph.py -> build/lib/networkx/algorithms/isomorphism
      creating build/lib/networkx/algorithms/shortest_paths
      copying networkx/algorithms/shortest_paths/__init__.py -> build/lib/networkx/algorithms/shortest_paths
      copying networkx/algorithms/shortest_paths/unweighted.py -> build/lib/networkx/algorithms/shortest_paths
      copying networkx/algorithms/shortest_paths/weighted.py -> build/lib/networkx/algorithms/shortest_paths
      copying networkx/algorithms/shortest_paths/generic.py -> build/lib/networkx/algorithms/shortest_paths
      copying networkx/algorithms/shortest_paths/astar.py -> build/lib/networkx/algorithms/shortest_paths
      copying networkx/algorithms/shortest_paths/dense.py -> build/lib/networkx/algorithms/shortest_paths
      creating build/lib/networkx/algorithms/link_analysis
      copying networkx/algorithms/link_analysis/__init__.py -> build/lib/networkx/algorithms/link_analysis
      copying networkx/algorithms/link_analysis/hits_alg.py -> build/lib/networkx/algorithms/link_analysis
      copying networkx/algorithms/link_analysis/pagerank_alg.py -> build/lib/networkx/algorithms/link_analysis
      creating build/lib/networkx/algorithms/operators
      copying networkx/algorithms/operators/__init__.py -> build/lib/networkx/algorithms/operators
      copying networkx/algorithms/operators/all.py -> build/lib/networkx/algorithms/operators
      copying networkx/algorithms/operators/unary.py -> build/lib/networkx/algorithms/operators
      copying networkx/algorithms/operators/product.py -> build/lib/networkx/algorithms/operators
      copying networkx/algorithms/operators/binary.py -> build/lib/networkx/algorithms/operators
      creating build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/kcomponents.py -> build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/independent_set.py -> build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/__init__.py -> build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/ramsey.py -> build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/vertex_cover.py -> build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/clique.py -> build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/clustering_coefficient.py -> build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/connectivity.py -> build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/dominating_set.py -> build/lib/networkx/algorithms/approximation
      copying networkx/algorithms/approximation/matching.py -> build/lib/networkx/algorithms/approximation
      creating build/lib/networkx/algorithms/tree
      copying networkx/algorithms/tree/branchings.py -> build/lib/networkx/algorithms/tree
      copying networkx/algorithms/tree/recognition.py -> build/lib/networkx/algorithms/tree
      copying networkx/algorithms/tree/__init__.py -> build/lib/networkx/algorithms/tree
      creating build/lib/networkx/classes
      copying networkx/classes/__init__.py -> build/lib/networkx/classes
      copying networkx/classes/function.py -> build/lib/networkx/classes
      copying networkx/classes/multidigraph.py -> build/lib/networkx/classes
      copying networkx/classes/digraph.py -> build/lib/networkx/classes
      copying networkx/classes/ordered.py -> build/lib/networkx/classes
      copying networkx/classes/multigraph.py -> build/lib/networkx/classes
      copying networkx/classes/graph.py -> build/lib/networkx/classes
      creating build/lib/networkx/external
      copying networkx/external/__init__.py -> build/lib/networkx/external
      creating build/lib/networkx/generators
      copying networkx/generators/__init__.py -> build/lib/networkx/generators
      copying networkx/generators/directed.py -> build/lib/networkx/generators
      copying networkx/generators/intersection.py -> build/lib/networkx/generators
      copying networkx/generators/classic.py -> build/lib/networkx/generators
      copying networkx/generators/social.py -> build/lib/networkx/generators
      copying networkx/generators/community.py -> build/lib/networkx/generators
      copying networkx/generators/expanders.py -> build/lib/networkx/generators
      copying networkx/generators/atlas.py -> build/lib/networkx/generators
      copying networkx/generators/small.py -> build/lib/networkx/generators
      copying networkx/generators/degree_seq.py -> build/lib/networkx/generators
      copying networkx/generators/random_graphs.py -> build/lib/networkx/generators
      copying networkx/generators/geometric.py -> build/lib/networkx/generators
      copying networkx/generators/random_clustered.py -> build/lib/networkx/generators
      copying networkx/generators/line.py -> build/lib/networkx/generators
      copying networkx/generators/stochastic.py -> build/lib/networkx/generators
      copying networkx/generators/ego.py -> build/lib/networkx/generators
      copying networkx/generators/threshold.py -> build/lib/networkx/generators
      copying networkx/generators/nonisomorphic_trees.py -> build/lib/networkx/generators
      creating build/lib/networkx/drawing
      copying networkx/drawing/__init__.py -> build/lib/networkx/drawing
      copying networkx/drawing/nx_agraph.py -> build/lib/networkx/drawing
      copying networkx/drawing/nx_pylab.py -> build/lib/networkx/drawing
      copying networkx/drawing/nx_pydot.py -> build/lib/networkx/drawing
      copying networkx/drawing/layout.py -> build/lib/networkx/drawing
      creating build/lib/networkx/linalg
      copying networkx/linalg/attrmatrix.py -> build/lib/networkx/linalg
      copying networkx/linalg/laplacianmatrix.py -> build/lib/networkx/linalg
      copying networkx/linalg/algebraicconnectivity.py -> build/lib/networkx/linalg
      copying networkx/linalg/__init__.py -> build/lib/networkx/linalg
      copying networkx/linalg/graphmatrix.py -> build/lib/networkx/linalg
      copying networkx/linalg/modularitymatrix.py -> build/lib/networkx/linalg
      copying networkx/linalg/spectrum.py -> build/lib/networkx/linalg
      creating build/lib/networkx/readwrite
      copying networkx/readwrite/p2g.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/multiline_adjlist.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/__init__.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/leda.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/graphml.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/pajek.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/gexf.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/gpickle.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/adjlist.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/sparse6.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/nx_yaml.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/nx_shp.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/graph6.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/edgelist.py -> build/lib/networkx/readwrite
      copying networkx/readwrite/gml.py -> build/lib/networkx/readwrite
      creating build/lib/networkx/readwrite/json_graph
      copying networkx/readwrite/json_graph/__init__.py -> build/lib/networkx/readwrite/json_graph
      copying networkx/readwrite/json_graph/tree.py -> build/lib/networkx/readwrite/json_graph
      copying networkx/readwrite/json_graph/adjacency.py -> build/lib/networkx/readwrite/json_graph
      copying networkx/readwrite/json_graph/node_link.py -> build/lib/networkx/readwrite/json_graph
      creating build/lib/networkx/tests
      copying networkx/tests/test.py -> build/lib/networkx/tests
      copying networkx/tests/test_convert_scipy.py -> build/lib/networkx/tests
      copying networkx/tests/__init__.py -> build/lib/networkx/tests
      copying networkx/tests/test_convert.py -> build/lib/networkx/tests
      copying networkx/tests/test_exceptions.py -> build/lib/networkx/tests
      copying networkx/tests/test_convert_numpy.py -> build/lib/networkx/tests
      copying networkx/tests/test_relabel.py -> build/lib/networkx/tests
      copying networkx/tests/test_convert_pandas.py -> build/lib/networkx/tests
      copying networkx/tests/benchmark.py -> build/lib/networkx/tests
      creating build/lib/networkx/testing
      copying networkx/testing/__init__.py -> build/lib/networkx/testing
      copying networkx/testing/utils.py -> build/lib/networkx/testing
      creating build/lib/networkx/utils
      copying networkx/utils/heaps.py -> build/lib/networkx/utils
      copying networkx/utils/random_sequence.py -> build/lib/networkx/utils
      copying networkx/utils/__init__.py -> build/lib/networkx/utils
      copying networkx/utils/misc.py -> build/lib/networkx/utils
      copying networkx/utils/decorators.py -> build/lib/networkx/utils
      copying networkx/utils/contextmanagers.py -> build/lib/networkx/utils
      copying networkx/utils/rcm.py -> build/lib/networkx/utils
      copying networkx/utils/union_find.py -> build/lib/networkx/utils
      creating build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_dominating.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_distance_regular.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_mis.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_block.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_euler.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_distance_measures.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_mst.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_clique.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_dominance.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_richclub.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_smetric.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_vitality.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_minors.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_swap.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_cluster.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_link_prediction.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_triads.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_boundary.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_hierarchy.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_dag.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_simple_paths.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_cycles.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_graphical.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_matching.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_core.py -> build/lib/networkx/algorithms/tests
      copying networkx/algorithms/tests/test_hybrid.py -> build/lib/networkx/algorithms/tests
      creating build/lib/networkx/algorithms/assortativity/tests
      copying networkx/algorithms/assortativity/tests/test_pairs.py -> build/lib/networkx/algorithms/assortativity/tests
      copying networkx/algorithms/assortativity/tests/test_connectivity.py -> build/lib/networkx/algorithms/assortativity/tests
      copying networkx/algorithms/assortativity/tests/test_correlation.py -> build/lib/networkx/algorithms/assortativity/tests
      copying networkx/algorithms/assortativity/tests/test_neighbor_degree.py -> build/lib/networkx/algorithms/assortativity/tests
      copying networkx/algorithms/assortativity/tests/base_test.py -> build/lib/networkx/algorithms/assortativity/tests
      copying networkx/algorithms/assortativity/tests/test_mixing.py -> build/lib/networkx/algorithms/assortativity/tests
      creating build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_edgelist.py -> build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_generators.py -> build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_centrality.py -> build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_basic.py -> build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_matrix.py -> build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_cluster.py -> build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_redundancy.py -> build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_spectral_bipartivity.py -> build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_project.py -> build/lib/networkx/algorithms/bipartite/tests
      copying networkx/algorithms/bipartite/tests/test_matching.py -> build/lib/networkx/algorithms/bipartite/tests
      creating build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_load_centrality.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_degree_centrality.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_betweenness_centrality.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_current_flow_betweenness_centrality_subset.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_betweenness_centrality_subset.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_katz_centrality.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_eigenvector_centrality.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_dispersion.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_current_flow_closeness.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_closeness_centrality.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_communicability.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_harmonic_centrality.py -> build/lib/networkx/algorithms/centrality/tests
      copying networkx/algorithms/centrality/tests/test_current_flow_betweenness_centrality.py -> build/lib/networkx/algorithms/centrality/tests
      creating build/lib/networkx/algorithms/chordal/tests
      copying networkx/algorithms/chordal/tests/test_chordal.py -> build/lib/networkx/algorithms/chordal/tests
      creating build/lib/networkx/algorithms/community/tests
      copying networkx/algorithms/community/tests/test_kclique.py -> build/lib/networkx/algorithms/community/tests
      creating build/lib/networkx/algorithms/components/tests
      copying networkx/algorithms/components/tests/test_connected.py -> build/lib/networkx/algorithms/components/tests
      copying networkx/algorithms/components/tests/test_attracting.py -> build/lib/networkx/algorithms/components/tests
      copying networkx/algorithms/components/tests/test_semiconnected.py -> build/lib/networkx/algorithms/components/tests
      copying networkx/algorithms/components/tests/test_strongly_connected.py -> build/lib/networkx/algorithms/components/tests
      copying networkx/algorithms/components/tests/test_weakly_connected.py -> build/lib/networkx/algorithms/components/tests
      copying networkx/algorithms/components/tests/test_subgraph_copies.py -> build/lib/networkx/algorithms/components/tests
      copying networkx/algorithms/components/tests/test_biconnected.py -> build/lib/networkx/algorithms/components/tests
      creating build/lib/networkx/algorithms/connectivity/tests
      copying networkx/algorithms/connectivity/tests/test_connectivity.py -> build/lib/networkx/algorithms/connectivity/tests
      copying networkx/algorithms/connectivity/tests/test_kcutsets.py -> build/lib/networkx/algorithms/connectivity/tests
      copying networkx/algorithms/connectivity/tests/test_stoer_wagner.py -> build/lib/networkx/algorithms/connectivity/tests
      copying networkx/algorithms/connectivity/tests/test_cuts.py -> build/lib/networkx/algorithms/connectivity/tests
      copying networkx/algorithms/connectivity/tests/test_kcomponents.py -> build/lib/networkx/algorithms/connectivity/tests
      creating build/lib/networkx/algorithms/coloring/tests
      copying networkx/algorithms/coloring/tests/test_coloring.py -> build/lib/networkx/algorithms/coloring/tests
      creating build/lib/networkx/algorithms/flow/tests
      copying networkx/algorithms/flow/tests/test_maxflow_large_graph.py -> build/lib/networkx/algorithms/flow/tests
      copying networkx/algorithms/flow/tests/test_mincost.py -> build/lib/networkx/algorithms/flow/tests
      copying networkx/algorithms/flow/tests/test_maxflow.py -> build/lib/networkx/algorithms/flow/tests
      copying networkx/algorithms/flow/tests/gw1.gpickle.bz2 -> build/lib/networkx/algorithms/flow/tests
      copying networkx/algorithms/flow/tests/gl1.gpickle.bz2 -> build/lib/networkx/algorithms/flow/tests
      copying networkx/algorithms/flow/tests/wlm3.gpickle.bz2 -> build/lib/networkx/algorithms/flow/tests
      copying networkx/algorithms/flow/tests/netgen-2.gpickle.bz2 -> build/lib/networkx/algorithms/flow/tests
      creating build/lib/networkx/algorithms/traversal/tests
      copying networkx/algorithms/traversal/tests/test_bfs.py -> build/lib/networkx/algorithms/traversal/tests
      copying networkx/algorithms/traversal/tests/test_dfs.py -> build/lib/networkx/algorithms/traversal/tests
      copying networkx/algorithms/traversal/tests/test_edgedfs.py -> build/lib/networkx/algorithms/traversal/tests
      creating build/lib/networkx/algorithms/isomorphism/tests
      copying networkx/algorithms/isomorphism/tests/test_vf2userfunc.py -> build/lib/networkx/algorithms/isomorphism/tests
      copying networkx/algorithms/isomorphism/tests/test_isomorphvf2.py -> build/lib/networkx/algorithms/isomorphism/tests
      copying networkx/algorithms/isomorphism/tests/test_isomorphism.py -> build/lib/networkx/algorithms/isomorphism/tests
      copying networkx/algorithms/isomorphism/tests/iso_r01_s80.A99 -> build/lib/networkx/algorithms/isomorphism/tests
      copying networkx/algorithms/isomorphism/tests/si2_b06_m200.B99 -> build/lib/networkx/algorithms/isomorphism/tests
      copying networkx/algorithms/isomorphism/tests/si2_b06_m200.A99 -> build/lib/networkx/algorithms/isomorphism/tests
      copying networkx/algorithms/isomorphism/tests/iso_r01_s80.B99 -> build/lib/networkx/algorithms/isomorphism/tests
      creating build/lib/networkx/algorithms/shortest_paths/tests
      copying networkx/algorithms/shortest_paths/tests/test_astar.py -> build/lib/networkx/algorithms/shortest_paths/tests
      copying networkx/algorithms/shortest_paths/tests/test_generic.py -> build/lib/networkx/algorithms/shortest_paths/tests
      copying networkx/algorithms/shortest_paths/tests/test_unweighted.py -> build/lib/networkx/algorithms/shortest_paths/tests
      copying networkx/algorithms/shortest_paths/tests/test_weighted.py -> build/lib/networkx/algorithms/shortest_paths/tests
      copying networkx/algorithms/shortest_paths/tests/test_dense_numpy.py -> build/lib/networkx/algorithms/shortest_paths/tests
      copying networkx/algorithms/shortest_paths/tests/test_dense.py -> build/lib/networkx/algorithms/shortest_paths/tests
      creating build/lib/networkx/algorithms/link_analysis/tests
      copying networkx/algorithms/link_analysis/tests/test_hits.py -> build/lib/networkx/algorithms/link_analysis/tests
      copying networkx/algorithms/link_analysis/tests/test_pagerank.py -> build/lib/networkx/algorithms/link_analysis/tests
      creating build/lib/networkx/algorithms/operators/tests
      copying networkx/algorithms/operators/tests/test_binary.py -> build/lib/networkx/algorithms/operators/tests
      copying networkx/algorithms/operators/tests/test_product.py -> build/lib/networkx/algorithms/operators/tests
      copying networkx/algorithms/operators/tests/test_all.py -> build/lib/networkx/algorithms/operators/tests
      copying networkx/algorithms/operators/tests/test_unary.py -> build/lib/networkx/algorithms/operators/tests
      creating build/lib/networkx/algorithms/approximation/tests
      copying networkx/algorithms/approximation/tests/test_approx_clust_coeff.py -> build/lib/networkx/algorithms/approximation/tests
      copying networkx/algorithms/approximation/tests/test_dominating_set.py -> build/lib/networkx/algorithms/approximation/tests
      copying networkx/algorithms/approximation/tests/test_connectivity.py -> build/lib/networkx/algorithms/approximation/tests
      copying networkx/algorithms/approximation/tests/test_clique.py -> build/lib/networkx/algorithms/approximation/tests
      copying networkx/algorithms/approximation/tests/test_independent_set.py -> build/lib/networkx/algorithms/approximation/tests
      copying networkx/algorithms/approximation/tests/test_vertex_cover.py -> build/lib/networkx/algorithms/approximation/tests
      copying networkx/algorithms/approximation/tests/test_ramsey.py -> build/lib/networkx/algorithms/approximation/tests
      copying networkx/algorithms/approximation/tests/test_kcomponents.py -> build/lib/networkx/algorithms/approximation/tests
      copying networkx/algorithms/approximation/tests/test_matching.py -> build/lib/networkx/algorithms/approximation/tests
      creating build/lib/networkx/algorithms/tree/tests
      copying networkx/algorithms/tree/tests/test_branchings.py -> build/lib/networkx/algorithms/tree/tests
      copying networkx/algorithms/tree/tests/test_recognition.py -> build/lib/networkx/algorithms/tree/tests
      creating build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_graph_historical.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_multidigraph.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_digraph.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_digraph_historical.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/historical_tests.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_multigraph.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_timing.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_special.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_function.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_ordered.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/timingclasses.py -> build/lib/networkx/classes/tests
      copying networkx/classes/tests/test_graph.py -> build/lib/networkx/classes/tests
      creating build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_random_clustered.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_random_graphs.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_ego.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_atlas.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_degree_seq.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_directed.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_stochastic.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_geometric.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_threshold.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_nonisomorphic_trees.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_intersection.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_line.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_small.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_community.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_expanders.py -> build/lib/networkx/generators/tests
      copying networkx/generators/tests/test_classic.py -> build/lib/networkx/generators/tests
      creating build/lib/networkx/drawing/tests
      copying networkx/drawing/tests/test_layout.py -> build/lib/networkx/drawing/tests
      copying networkx/drawing/tests/test_agraph.py -> build/lib/networkx/drawing/tests
      copying networkx/drawing/tests/test_pylab.py -> build/lib/networkx/drawing/tests
      copying networkx/drawing/tests/test_pydot.py -> build/lib/networkx/drawing/tests
      creating build/lib/networkx/linalg/tests
      copying networkx/linalg/tests/test_spectrum.py -> build/lib/networkx/linalg/tests
      copying networkx/linalg/tests/test_laplacian.py -> build/lib/networkx/linalg/tests
      copying networkx/linalg/tests/test_graphmatrix.py -> build/lib/networkx/linalg/tests
      copying networkx/linalg/tests/test_modularity.py -> build/lib/networkx/linalg/tests
      copying networkx/linalg/tests/test_algebraic_connectivity.py -> build/lib/networkx/linalg/tests
      creating build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_edgelist.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_sparse6.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_yaml.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_gpickle.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_shp.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_adjlist.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_graphml.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_graph6.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_gml.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_p2g.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_gexf.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_leda.py -> build/lib/networkx/readwrite/tests
      copying networkx/readwrite/tests/test_pajek.py -> build/lib/networkx/readwrite/tests
      creating build/lib/networkx/readwrite/json_graph/tests
      copying networkx/readwrite/json_graph/tests/test_node_link.py -> build/lib/networkx/readwrite/json_graph/tests
      copying networkx/readwrite/json_graph/tests/test_adjacency.py -> build/lib/networkx/readwrite/json_graph/tests
      copying networkx/readwrite/json_graph/tests/test_tree.py -> build/lib/networkx/readwrite/json_graph/tests
      creating build/lib/networkx/testing/tests
      copying networkx/testing/tests/test_utils.py -> build/lib/networkx/testing/tests
      creating build/lib/networkx/utils/tests
      copying networkx/utils/tests/test_random_sequence.py -> build/lib/networkx/utils/tests
      copying networkx/utils/tests/test_unionfind.py -> build/lib/networkx/utils/tests
      copying networkx/utils/tests/test_misc.py -> build/lib/networkx/utils/tests
      copying networkx/utils/tests/test_heaps.py -> build/lib/networkx/utils/tests
      copying networkx/utils/tests/test_decorators.py -> build/lib/networkx/utils/tests
      copying networkx/utils/tests/test_rcm.py -> build/lib/networkx/utils/tests
      copying networkx/utils/tests/test_contextmanager.py -> build/lib/networkx/utils/tests
      /usr/local/cloudstor/python/pre/setuptools/command/install.py:34: SetuptoolsDeprecationWarning: setup.py install is deprecated. Use build and pip and other standards-based tools.
        warnings.warn(
      installing to build/bdist.linux-x86_64/wheel
      running install
      running install_lib
      creating build/bdist.linux-x86_64
      creating build/bdist.linux-x86_64/wheel
      creating build/bdist.linux-x86_64/wheel/networkx
      copying build/lib/networkx/version.py -> build/bdist.linux-x86_64/wheel/networkx
      copying build/lib/networkx/exception.py -> build/bdist.linux-x86_64/wheel/networkx
      creating build/bdist.linux-x86_64/wheel/networkx/external
      copying build/lib/networkx/external/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/external
      creating build/bdist.linux-x86_64/wheel/networkx/drawing
      copying build/lib/networkx/drawing/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/drawing
      copying build/lib/networkx/drawing/nx_agraph.py -> build/bdist.linux-x86_64/wheel/networkx/drawing
      copying build/lib/networkx/drawing/nx_pylab.py -> build/bdist.linux-x86_64/wheel/networkx/drawing
      copying build/lib/networkx/drawing/nx_pydot.py -> build/bdist.linux-x86_64/wheel/networkx/drawing
      copying build/lib/networkx/drawing/layout.py -> build/bdist.linux-x86_64/wheel/networkx/drawing
      creating build/bdist.linux-x86_64/wheel/networkx/drawing/tests
      copying build/lib/networkx/drawing/tests/test_layout.py -> build/bdist.linux-x86_64/wheel/networkx/drawing/tests
      copying build/lib/networkx/drawing/tests/test_agraph.py -> build/bdist.linux-x86_64/wheel/networkx/drawing/tests
      copying build/lib/networkx/drawing/tests/test_pylab.py -> build/bdist.linux-x86_64/wheel/networkx/drawing/tests
      copying build/lib/networkx/drawing/tests/test_pydot.py -> build/bdist.linux-x86_64/wheel/networkx/drawing/tests
      copying build/lib/networkx/__init__.py -> build/bdist.linux-x86_64/wheel/networkx
      creating build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/p2g.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/multiline_adjlist.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/leda.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/graphml.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/pajek.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/gexf.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/gpickle.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/adjlist.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/sparse6.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/nx_yaml.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/nx_shp.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      copying build/lib/networkx/readwrite/graph6.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      creating build/bdist.linux-x86_64/wheel/networkx/readwrite/json_graph
      copying build/lib/networkx/readwrite/json_graph/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/json_graph
      copying build/lib/networkx/readwrite/json_graph/tree.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/json_graph
      copying build/lib/networkx/readwrite/json_graph/adjacency.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/json_graph
      copying build/lib/networkx/readwrite/json_graph/node_link.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/json_graph
      creating build/bdist.linux-x86_64/wheel/networkx/readwrite/json_graph/tests
      copying build/lib/networkx/readwrite/json_graph/tests/test_node_link.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/json_graph/tests
      copying build/lib/networkx/readwrite/json_graph/tests/test_adjacency.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/json_graph/tests
      copying build/lib/networkx/readwrite/json_graph/tests/test_tree.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/json_graph/tests
      copying build/lib/networkx/readwrite/edgelist.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      creating build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_edgelist.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_sparse6.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_yaml.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_gpickle.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_shp.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_adjlist.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_graphml.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_graph6.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_gml.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_p2g.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_gexf.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_leda.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/tests/test_pajek.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite/tests
      copying build/lib/networkx/readwrite/gml.py -> build/bdist.linux-x86_64/wheel/networkx/readwrite
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/swap.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/hybrid.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/isolate.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/coloring
      copying build/lib/networkx/algorithms/coloring/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/coloring
      copying build/lib/networkx/algorithms/coloring/greedy_coloring.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/coloring
      copying build/lib/networkx/algorithms/coloring/greedy_coloring_with_interchange.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/coloring
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/coloring/tests
      copying build/lib/networkx/algorithms/coloring/tests/test_coloring.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/coloring/tests
      copying build/lib/networkx/algorithms/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/cycles.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/link_prediction.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/mis.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/tree
      copying build/lib/networkx/algorithms/tree/branchings.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tree
      copying build/lib/networkx/algorithms/tree/recognition.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tree
      copying build/lib/networkx/algorithms/tree/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tree
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/tree/tests
      copying build/lib/networkx/algorithms/tree/tests/test_branchings.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tree/tests
      copying build/lib/networkx/algorithms/tree/tests/test_recognition.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tree/tests
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism
      copying build/lib/networkx/algorithms/isomorphism/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism
      copying build/lib/networkx/algorithms/isomorphism/isomorphvf2.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism
      copying build/lib/networkx/algorithms/isomorphism/vf2userfunc.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism
      copying build/lib/networkx/algorithms/isomorphism/matchhelpers.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism
      copying build/lib/networkx/algorithms/isomorphism/isomorph.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism/tests
      copying build/lib/networkx/algorithms/isomorphism/tests/iso_r01_s80.A99 -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism/tests
      copying build/lib/networkx/algorithms/isomorphism/tests/si2_b06_m200.B99 -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism/tests
      copying build/lib/networkx/algorithms/isomorphism/tests/si2_b06_m200.A99 -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism/tests
      copying build/lib/networkx/algorithms/isomorphism/tests/test_vf2userfunc.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism/tests
      copying build/lib/networkx/algorithms/isomorphism/tests/iso_r01_s80.B99 -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism/tests
      copying build/lib/networkx/algorithms/isomorphism/tests/test_isomorphvf2.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism/tests
      copying build/lib/networkx/algorithms/isomorphism/tests/test_isomorphism.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/isomorphism/tests
      copying build/lib/networkx/algorithms/dag.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/distance_measures.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      copying build/lib/networkx/algorithms/flow/networksimplex.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      copying build/lib/networkx/algorithms/flow/edmondskarp.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      copying build/lib/networkx/algorithms/flow/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      copying build/lib/networkx/algorithms/flow/shortestaugmentingpath.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      copying build/lib/networkx/algorithms/flow/maxflow.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      copying build/lib/networkx/algorithms/flow/capacityscaling.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      copying build/lib/networkx/algorithms/flow/mincost.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      copying build/lib/networkx/algorithms/flow/utils.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      copying build/lib/networkx/algorithms/flow/preflowpush.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/flow/tests
      copying build/lib/networkx/algorithms/flow/tests/gw1.gpickle.bz2 -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow/tests
      copying build/lib/networkx/algorithms/flow/tests/test_maxflow_large_graph.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow/tests
      copying build/lib/networkx/algorithms/flow/tests/gl1.gpickle.bz2 -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow/tests
      copying build/lib/networkx/algorithms/flow/tests/test_mincost.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow/tests
      copying build/lib/networkx/algorithms/flow/tests/wlm3.gpickle.bz2 -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow/tests
      copying build/lib/networkx/algorithms/flow/tests/test_maxflow.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow/tests
      copying build/lib/networkx/algorithms/flow/tests/netgen-2.gpickle.bz2 -> build/bdist.linux-x86_64/wheel/networkx/algorithms/flow/tests
      copying build/lib/networkx/algorithms/dominating.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths
      copying build/lib/networkx/algorithms/shortest_paths/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths
      copying build/lib/networkx/algorithms/shortest_paths/unweighted.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths
      copying build/lib/networkx/algorithms/shortest_paths/weighted.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths
      copying build/lib/networkx/algorithms/shortest_paths/generic.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths
      copying build/lib/networkx/algorithms/shortest_paths/astar.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths/tests
      copying build/lib/networkx/algorithms/shortest_paths/tests/test_astar.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths/tests
      copying build/lib/networkx/algorithms/shortest_paths/tests/test_generic.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths/tests
      copying build/lib/networkx/algorithms/shortest_paths/tests/test_unweighted.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths/tests
      copying build/lib/networkx/algorithms/shortest_paths/tests/test_weighted.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths/tests
      copying build/lib/networkx/algorithms/shortest_paths/tests/test_dense_numpy.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths/tests
      copying build/lib/networkx/algorithms/shortest_paths/tests/test_dense.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths/tests
      copying build/lib/networkx/algorithms/shortest_paths/dense.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/shortest_paths
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/kcomponents.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/independent_set.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/ramsey.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/vertex_cover.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/clique.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/clustering_coefficient.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/connectivity.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/dominating_set.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      copying build/lib/networkx/algorithms/approximation/matching.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      copying build/lib/networkx/algorithms/approximation/tests/test_approx_clust_coeff.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      copying build/lib/networkx/algorithms/approximation/tests/test_dominating_set.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      copying build/lib/networkx/algorithms/approximation/tests/test_connectivity.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      copying build/lib/networkx/algorithms/approximation/tests/test_clique.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      copying build/lib/networkx/algorithms/approximation/tests/test_independent_set.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      copying build/lib/networkx/algorithms/approximation/tests/test_vertex_cover.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      copying build/lib/networkx/algorithms/approximation/tests/test_ramsey.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      copying build/lib/networkx/algorithms/approximation/tests/test_kcomponents.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      copying build/lib/networkx/algorithms/approximation/tests/test_matching.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/approximation/tests
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/link_analysis
      copying build/lib/networkx/algorithms/link_analysis/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/link_analysis
      copying build/lib/networkx/algorithms/link_analysis/hits_alg.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/link_analysis
      copying build/lib/networkx/algorithms/link_analysis/pagerank_alg.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/link_analysis
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/link_analysis/tests
      copying build/lib/networkx/algorithms/link_analysis/tests/test_hits.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/link_analysis/tests
      copying build/lib/networkx/algorithms/link_analysis/tests/test_pagerank.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/link_analysis/tests
      copying build/lib/networkx/algorithms/clique.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/minors.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity
      copying build/lib/networkx/algorithms/assortativity/correlation.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity
      copying build/lib/networkx/algorithms/assortativity/neighbor_degree.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity
      copying build/lib/networkx/algorithms/assortativity/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity
      copying build/lib/networkx/algorithms/assortativity/connectivity.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity
      copying build/lib/networkx/algorithms/assortativity/pairs.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity
      copying build/lib/networkx/algorithms/assortativity/mixing.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity/tests
      copying build/lib/networkx/algorithms/assortativity/tests/test_pairs.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity/tests
      copying build/lib/networkx/algorithms/assortativity/tests/test_connectivity.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity/tests
      copying build/lib/networkx/algorithms/assortativity/tests/test_correlation.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity/tests
      copying build/lib/networkx/algorithms/assortativity/tests/test_neighbor_degree.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity/tests
      copying build/lib/networkx/algorithms/assortativity/tests/base_test.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity/tests
      copying build/lib/networkx/algorithms/assortativity/tests/test_mixing.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/assortativity/tests
      copying build/lib/networkx/algorithms/boundary.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/mst.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/dominance.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/traversal
      copying build/lib/networkx/algorithms/traversal/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/traversal
      copying build/lib/networkx/algorithms/traversal/breadth_first_search.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/traversal
      copying build/lib/networkx/algorithms/traversal/depth_first_search.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/traversal
      copying build/lib/networkx/algorithms/traversal/edgedfs.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/traversal
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/traversal/tests
      copying build/lib/networkx/algorithms/traversal/tests/test_bfs.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/traversal/tests
      copying build/lib/networkx/algorithms/traversal/tests/test_dfs.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/traversal/tests
      copying build/lib/networkx/algorithms/traversal/tests/test_edgedfs.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/traversal/tests
      copying build/lib/networkx/algorithms/vitality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/block.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/components
      copying build/lib/networkx/algorithms/components/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components
      copying build/lib/networkx/algorithms/components/strongly_connected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components
      copying build/lib/networkx/algorithms/components/biconnected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components
      copying build/lib/networkx/algorithms/components/connected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components
      copying build/lib/networkx/algorithms/components/weakly_connected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components
      copying build/lib/networkx/algorithms/components/semiconnected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components
      copying build/lib/networkx/algorithms/components/attracting.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/components/tests
      copying build/lib/networkx/algorithms/components/tests/test_connected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components/tests
      copying build/lib/networkx/algorithms/components/tests/test_attracting.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components/tests
      copying build/lib/networkx/algorithms/components/tests/test_semiconnected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components/tests
      copying build/lib/networkx/algorithms/components/tests/test_strongly_connected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components/tests
      copying build/lib/networkx/algorithms/components/tests/test_weakly_connected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components/tests
      copying build/lib/networkx/algorithms/components/tests/test_subgraph_copies.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components/tests
      copying build/lib/networkx/algorithms/components/tests/test_biconnected.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/components/tests
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/chordal
      copying build/lib/networkx/algorithms/chordal/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/chordal
      copying build/lib/networkx/algorithms/chordal/chordal_alg.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/chordal
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/chordal/tests
      copying build/lib/networkx/algorithms/chordal/tests/test_chordal.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/chordal/tests
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/operators
      copying build/lib/networkx/algorithms/operators/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/operators
      copying build/lib/networkx/algorithms/operators/all.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/operators
      copying build/lib/networkx/algorithms/operators/unary.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/operators
      copying build/lib/networkx/algorithms/operators/product.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/operators
      copying build/lib/networkx/algorithms/operators/binary.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/operators
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/operators/tests
      copying build/lib/networkx/algorithms/operators/tests/test_binary.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/operators/tests
      copying build/lib/networkx/algorithms/operators/tests/test_product.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/operators/tests
      copying build/lib/networkx/algorithms/operators/tests/test_all.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/operators/tests
      copying build/lib/networkx/algorithms/operators/tests/test_unary.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/operators/tests
      copying build/lib/networkx/algorithms/richclub.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/distance_regular.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/core.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/graphical.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity
      copying build/lib/networkx/algorithms/connectivity/kcomponents.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity
      copying build/lib/networkx/algorithms/connectivity/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity
      copying build/lib/networkx/algorithms/connectivity/cuts.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity
      copying build/lib/networkx/algorithms/connectivity/stoerwagner.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity
      copying build/lib/networkx/algorithms/connectivity/kcutsets.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity
      copying build/lib/networkx/algorithms/connectivity/connectivity.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity
      copying build/lib/networkx/algorithms/connectivity/utils.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity/tests
      copying build/lib/networkx/algorithms/connectivity/tests/test_connectivity.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity/tests
      copying build/lib/networkx/algorithms/connectivity/tests/test_kcutsets.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity/tests
      copying build/lib/networkx/algorithms/connectivity/tests/test_stoer_wagner.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity/tests
      copying build/lib/networkx/algorithms/connectivity/tests/test_cuts.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity/tests
      copying build/lib/networkx/algorithms/connectivity/tests/test_kcomponents.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/connectivity/tests
      copying build/lib/networkx/algorithms/hierarchy.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/generators.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/matrix.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/spectral.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/redundancy.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/basic.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/projection.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/matching.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/bipartite/edgelist.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_edgelist.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_generators.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_basic.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_matrix.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_cluster.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_redundancy.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_spectral_bipartivity.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_project.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/tests/test_matching.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite/tests
      copying build/lib/networkx/algorithms/bipartite/cluster.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/bipartite
      copying build/lib/networkx/algorithms/smetric.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/community
      copying build/lib/networkx/algorithms/community/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/community
      copying build/lib/networkx/algorithms/community/kclique.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/community
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/community/tests
      copying build/lib/networkx/algorithms/community/tests/test_kclique.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/community/tests
      copying build/lib/networkx/algorithms/matching.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/triads.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/simple_paths.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      copying build/lib/networkx/algorithms/euler.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_dominating.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_distance_regular.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_mis.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_block.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_euler.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_distance_measures.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_mst.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_clique.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_dominance.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_richclub.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_smetric.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_vitality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_minors.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_swap.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_cluster.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_link_prediction.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_triads.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_boundary.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_hierarchy.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_dag.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_simple_paths.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_cycles.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_graphical.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_matching.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_core.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/tests/test_hybrid.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/tests
      copying build/lib/networkx/algorithms/cluster.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/flow_matrix.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/eigenvector.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/current_flow_betweenness.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/betweenness.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/katz.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/load.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/degree_alg.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/current_flow_closeness.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/betweenness_subset.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/closeness.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/harmonic.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/communicability_alg.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      copying build/lib/networkx/algorithms/centrality/current_flow_betweenness_subset.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      creating build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_load_centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_degree_centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_betweenness_centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_current_flow_betweenness_centrality_subset.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_betweenness_centrality_subset.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_katz_centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_eigenvector_centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_dispersion.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_current_flow_closeness.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_closeness_centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_communicability.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_harmonic_centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/tests/test_current_flow_betweenness_centrality.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality/tests
      copying build/lib/networkx/algorithms/centrality/dispersion.py -> build/bdist.linux-x86_64/wheel/networkx/algorithms/centrality
      creating build/bdist.linux-x86_64/wheel/networkx/utils
      copying build/lib/networkx/utils/heaps.py -> build/bdist.linux-x86_64/wheel/networkx/utils
      copying build/lib/networkx/utils/random_sequence.py -> build/bdist.linux-x86_64/wheel/networkx/utils
      copying build/lib/networkx/utils/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/utils
      copying build/lib/networkx/utils/misc.py -> build/bdist.linux-x86_64/wheel/networkx/utils
      copying build/lib/networkx/utils/decorators.py -> build/bdist.linux-x86_64/wheel/networkx/utils
      copying build/lib/networkx/utils/contextmanagers.py -> build/bdist.linux-x86_64/wheel/networkx/utils
      copying build/lib/networkx/utils/rcm.py -> build/bdist.linux-x86_64/wheel/networkx/utils
      copying build/lib/networkx/utils/union_find.py -> build/bdist.linux-x86_64/wheel/networkx/utils
      creating build/bdist.linux-x86_64/wheel/networkx/utils/tests
      copying build/lib/networkx/utils/tests/test_random_sequence.py -> build/bdist.linux-x86_64/wheel/networkx/utils/tests
      copying build/lib/networkx/utils/tests/test_unionfind.py -> build/bdist.linux-x86_64/wheel/networkx/utils/tests
      copying build/lib/networkx/utils/tests/test_misc.py -> build/bdist.linux-x86_64/wheel/networkx/utils/tests
      copying build/lib/networkx/utils/tests/test_heaps.py -> build/bdist.linux-x86_64/wheel/networkx/utils/tests
      copying build/lib/networkx/utils/tests/test_decorators.py -> build/bdist.linux-x86_64/wheel/networkx/utils/tests
      copying build/lib/networkx/utils/tests/test_rcm.py -> build/bdist.linux-x86_64/wheel/networkx/utils/tests
      copying build/lib/networkx/utils/tests/test_contextmanager.py -> build/bdist.linux-x86_64/wheel/networkx/utils/tests
      creating build/bdist.linux-x86_64/wheel/networkx/testing
      copying build/lib/networkx/testing/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/testing
      copying build/lib/networkx/testing/utils.py -> build/bdist.linux-x86_64/wheel/networkx/testing
      creating build/bdist.linux-x86_64/wheel/networkx/testing/tests
      copying build/lib/networkx/testing/tests/test_utils.py -> build/bdist.linux-x86_64/wheel/networkx/testing/tests
      creating build/bdist.linux-x86_64/wheel/networkx/classes
      copying build/lib/networkx/classes/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/classes
      copying build/lib/networkx/classes/function.py -> build/bdist.linux-x86_64/wheel/networkx/classes
      copying build/lib/networkx/classes/multidigraph.py -> build/bdist.linux-x86_64/wheel/networkx/classes
      copying build/lib/networkx/classes/digraph.py -> build/bdist.linux-x86_64/wheel/networkx/classes
      copying build/lib/networkx/classes/ordered.py -> build/bdist.linux-x86_64/wheel/networkx/classes
      copying build/lib/networkx/classes/multigraph.py -> build/bdist.linux-x86_64/wheel/networkx/classes
      copying build/lib/networkx/classes/graph.py -> build/bdist.linux-x86_64/wheel/networkx/classes
      creating build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_graph_historical.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_multidigraph.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_digraph.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_digraph_historical.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/historical_tests.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_multigraph.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_timing.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_special.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_function.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_ordered.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/timingclasses.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/classes/tests/test_graph.py -> build/bdist.linux-x86_64/wheel/networkx/classes/tests
      copying build/lib/networkx/convert_matrix.py -> build/bdist.linux-x86_64/wheel/networkx
      creating build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/directed.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/intersection.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/classic.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/social.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/community.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/expanders.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/atlas.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/small.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/degree_seq.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/random_graphs.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/geometric.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/random_clustered.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/line.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/stochastic.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/ego.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/generators/threshold.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      creating build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_random_clustered.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_random_graphs.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_ego.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_atlas.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_degree_seq.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_directed.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_stochastic.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_geometric.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_threshold.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_nonisomorphic_trees.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_intersection.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_line.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_small.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_community.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_expanders.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/tests/test_classic.py -> build/bdist.linux-x86_64/wheel/networkx/generators/tests
      copying build/lib/networkx/generators/nonisomorphic_trees.py -> build/bdist.linux-x86_64/wheel/networkx/generators
      copying build/lib/networkx/relabel.py -> build/bdist.linux-x86_64/wheel/networkx
      copying build/lib/networkx/convert.py -> build/bdist.linux-x86_64/wheel/networkx
      copying build/lib/networkx/release.py -> build/bdist.linux-x86_64/wheel/networkx
      creating build/bdist.linux-x86_64/wheel/networkx/linalg
      copying build/lib/networkx/linalg/attrmatrix.py -> build/bdist.linux-x86_64/wheel/networkx/linalg
      copying build/lib/networkx/linalg/laplacianmatrix.py -> build/bdist.linux-x86_64/wheel/networkx/linalg
      copying build/lib/networkx/linalg/algebraicconnectivity.py -> build/bdist.linux-x86_64/wheel/networkx/linalg
      copying build/lib/networkx/linalg/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/linalg
      copying build/lib/networkx/linalg/graphmatrix.py -> build/bdist.linux-x86_64/wheel/networkx/linalg
      copying build/lib/networkx/linalg/modularitymatrix.py -> build/bdist.linux-x86_64/wheel/networkx/linalg
      copying build/lib/networkx/linalg/spectrum.py -> build/bdist.linux-x86_64/wheel/networkx/linalg
      creating build/bdist.linux-x86_64/wheel/networkx/linalg/tests
      copying build/lib/networkx/linalg/tests/test_spectrum.py -> build/bdist.linux-x86_64/wheel/networkx/linalg/tests
      copying build/lib/networkx/linalg/tests/test_laplacian.py -> build/bdist.linux-x86_64/wheel/networkx/linalg/tests
      copying build/lib/networkx/linalg/tests/test_graphmatrix.py -> build/bdist.linux-x86_64/wheel/networkx/linalg/tests
      copying build/lib/networkx/linalg/tests/test_modularity.py -> build/bdist.linux-x86_64/wheel/networkx/linalg/tests
      copying build/lib/networkx/linalg/tests/test_algebraic_connectivity.py -> build/bdist.linux-x86_64/wheel/networkx/linalg/tests
      creating build/bdist.linux-x86_64/wheel/networkx/tests
      copying build/lib/networkx/tests/test.py -> build/bdist.linux-x86_64/wheel/networkx/tests
      copying build/lib/networkx/tests/test_convert_scipy.py -> build/bdist.linux-x86_64/wheel/networkx/tests
      copying build/lib/networkx/tests/__init__.py -> build/bdist.linux-x86_64/wheel/networkx/tests
      copying build/lib/networkx/tests/test_convert.py -> build/bdist.linux-x86_64/wheel/networkx/tests
      copying build/lib/networkx/tests/test_exceptions.py -> build/bdist.linux-x86_64/wheel/networkx/tests
      copying build/lib/networkx/tests/test_convert_numpy.py -> build/bdist.linux-x86_64/wheel/networkx/tests
      copying build/lib/networkx/tests/test_relabel.py -> build/bdist.linux-x86_64/wheel/networkx/tests
      copying build/lib/networkx/tests/test_convert_pandas.py -> build/bdist.linux-x86_64/wheel/networkx/tests
      copying build/lib/networkx/tests/benchmark.py -> build/bdist.linux-x86_64/wheel/networkx/tests
      running install_data
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10
      copying INSTALL.txt -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10
      copying LICENSE.txt -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/advanced
      copying examples/advanced/iterated_dynamical_systems.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/advanced
      copying examples/advanced/parallel_betweenness.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/advanced
      copying examples/advanced/heavy_metal_umlaut.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/advanced
      copying examples/advanced/eigenvalues.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/advanced
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms
      copying examples/algorithms/krackhardt_centrality.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms
      copying examples/algorithms/blockmodel.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms
      copying examples/algorithms/rcm.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms
      copying examples/algorithms/davis_club.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms
      copying examples/algorithms/hartford_drug.edgelist -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/basic
      copying examples/basic/read_write.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/basic
      copying examples/basic/properties.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/basic
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/3d_drawing
      copying examples/3d_drawing/mayavi2_spring.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/3d_drawing
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/unix_email.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/node_colormap.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/weighted_graph.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/simple_path.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/four_grids.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/sampson.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/atlas.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/edge_colormap.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/lanl_routes.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/circular_tree.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/labels_and_colors.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/giant_component.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/random_geometric_graph.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/chess_masters.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/house_with_colors.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/ego_graph.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/degree_histogram.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/knuth_miles.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/chess_masters_WCC.pgn.bz2 -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/knuth_miles.txt.gz -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/unix_email.mbox -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      copying examples/drawing/lanl_routes.edgelist -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/unix_email.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/words.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/atlas2.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/expected_degree_sequence.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/karate_club.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/erdos_renyi.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/roget.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/atlas.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/degree_sequence.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/napoleon_russian_campaign.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/football.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/knuth_miles.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/knuth_miles.txt.gz -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/words_dat.txt.gz -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/roget_dat.txt.gz -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      copying examples/graph/unix_email.mbox -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/multigraph
      copying examples/multigraph/chess_masters.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/multigraph
      copying examples/multigraph/chess_masters_WCC.pgn.bz2 -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/multigraph
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/pygraphviz
      copying examples/pygraphviz/write_dotfile.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/pygraphviz
      copying examples/pygraphviz/pygraphviz_draw.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/pygraphviz
      copying examples/pygraphviz/pygraphviz_attributes.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/pygraphviz
      copying examples/pygraphviz/pygraphviz_simple.py -> build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/pygraphviz
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.data/data/share/doc/networkx-1.10/examples/readwrite
      running install_egg_info
      running egg_info
      writing networkx.egg-info/PKG-INFO
      writing dependency_links to networkx.egg-info/dependency_links.txt
      writing requirements to networkx.egg-info/requires.txt
      writing top-level names to networkx.egg-info/top_level.txt
      listing git files failed - pretending there aren't any
      reading manifest file 'networkx.egg-info/SOURCES.txt'
      reading manifest template 'MANIFEST.in'
      warning: no files found matching 'scripts/*'
      warning: no files found matching 'networkx/tests/*.txt'
      warning: no files found matching 'networkx/*/*/tests/*.txt'
      warning: no previously-included files matching '*~' found anywhere in distribution
      warning: no previously-included files matching '*.pyc' found anywhere in distribution
      warning: no previously-included files matching '.svn' found anywhere in distribution
      no previously-included directories found matching 'doc/build'
      no previously-included directories found matching 'doc/source/reference/generated'
      no previously-included directories found matching 'doc/source/examples'
      no previously-included directories found matching 'doc/source/static/examples'
      no previously-included directories found matching 'doc/source/templates/gallery.html'
      adding license file 'LICENSE.txt'
      writing manifest file 'networkx.egg-info/SOURCES.txt'
      Copying networkx.egg-info to build/bdist.linux-x86_64/wheel/networkx-1.10-py3.9.egg-info
      running install_scripts
      adding license file "LICENSE.txt" (matched pattern "LICEN[CS]E*")
      creating build/bdist.linux-x86_64/wheel/networkx-1.10.dist-info/WHEEL
      creating '/tmp/pip-wheel-_brc872f/networkx-1.10-py2.py3-none-any.whl' and adding 'build/bdist.linux-x86_64/wheel' to it
      adding 'networkx/__init__.py'
      adding 'networkx/convert.py'
      adding 'networkx/convert_matrix.py'
      adding 'networkx/exception.py'
      adding 'networkx/relabel.py'
      adding 'networkx/release.py'
      adding 'networkx/version.py'
      adding 'networkx/algorithms/__init__.py'
      adding 'networkx/algorithms/block.py'
      adding 'networkx/algorithms/boundary.py'
      adding 'networkx/algorithms/clique.py'
      adding 'networkx/algorithms/cluster.py'
      adding 'networkx/algorithms/core.py'
      adding 'networkx/algorithms/cycles.py'
      adding 'networkx/algorithms/dag.py'
      adding 'networkx/algorithms/distance_measures.py'
      adding 'networkx/algorithms/distance_regular.py'
      adding 'networkx/algorithms/dominance.py'
      adding 'networkx/algorithms/dominating.py'
      adding 'networkx/algorithms/euler.py'
      adding 'networkx/algorithms/graphical.py'
      adding 'networkx/algorithms/hierarchy.py'
      adding 'networkx/algorithms/hybrid.py'
      adding 'networkx/algorithms/isolate.py'
      adding 'networkx/algorithms/link_prediction.py'
      adding 'networkx/algorithms/matching.py'
      adding 'networkx/algorithms/minors.py'
      adding 'networkx/algorithms/mis.py'
      adding 'networkx/algorithms/mst.py'
      adding 'networkx/algorithms/richclub.py'
      adding 'networkx/algorithms/simple_paths.py'
      adding 'networkx/algorithms/smetric.py'
      adding 'networkx/algorithms/swap.py'
      adding 'networkx/algorithms/triads.py'
      adding 'networkx/algorithms/vitality.py'
      adding 'networkx/algorithms/approximation/__init__.py'
      adding 'networkx/algorithms/approximation/clique.py'
      adding 'networkx/algorithms/approximation/clustering_coefficient.py'
      adding 'networkx/algorithms/approximation/connectivity.py'
      adding 'networkx/algorithms/approximation/dominating_set.py'
      adding 'networkx/algorithms/approximation/independent_set.py'
      adding 'networkx/algorithms/approximation/kcomponents.py'
      adding 'networkx/algorithms/approximation/matching.py'
      adding 'networkx/algorithms/approximation/ramsey.py'
      adding 'networkx/algorithms/approximation/vertex_cover.py'
      adding 'networkx/algorithms/approximation/tests/test_approx_clust_coeff.py'
      adding 'networkx/algorithms/approximation/tests/test_clique.py'
      adding 'networkx/algorithms/approximation/tests/test_connectivity.py'
      adding 'networkx/algorithms/approximation/tests/test_dominating_set.py'
      adding 'networkx/algorithms/approximation/tests/test_independent_set.py'
      adding 'networkx/algorithms/approximation/tests/test_kcomponents.py'
      adding 'networkx/algorithms/approximation/tests/test_matching.py'
      adding 'networkx/algorithms/approximation/tests/test_ramsey.py'
      adding 'networkx/algorithms/approximation/tests/test_vertex_cover.py'
      adding 'networkx/algorithms/assortativity/__init__.py'
      adding 'networkx/algorithms/assortativity/connectivity.py'
      adding 'networkx/algorithms/assortativity/correlation.py'
      adding 'networkx/algorithms/assortativity/mixing.py'
      adding 'networkx/algorithms/assortativity/neighbor_degree.py'
      adding 'networkx/algorithms/assortativity/pairs.py'
      adding 'networkx/algorithms/assortativity/tests/base_test.py'
      adding 'networkx/algorithms/assortativity/tests/test_connectivity.py'
      adding 'networkx/algorithms/assortativity/tests/test_correlation.py'
      adding 'networkx/algorithms/assortativity/tests/test_mixing.py'
      adding 'networkx/algorithms/assortativity/tests/test_neighbor_degree.py'
      adding 'networkx/algorithms/assortativity/tests/test_pairs.py'
      adding 'networkx/algorithms/bipartite/__init__.py'
      adding 'networkx/algorithms/bipartite/basic.py'
      adding 'networkx/algorithms/bipartite/centrality.py'
      adding 'networkx/algorithms/bipartite/cluster.py'
      adding 'networkx/algorithms/bipartite/edgelist.py'
      adding 'networkx/algorithms/bipartite/generators.py'
      adding 'networkx/algorithms/bipartite/matching.py'
      adding 'networkx/algorithms/bipartite/matrix.py'
      adding 'networkx/algorithms/bipartite/projection.py'
      adding 'networkx/algorithms/bipartite/redundancy.py'
      adding 'networkx/algorithms/bipartite/spectral.py'
      adding 'networkx/algorithms/bipartite/tests/test_basic.py'
      adding 'networkx/algorithms/bipartite/tests/test_centrality.py'
      adding 'networkx/algorithms/bipartite/tests/test_cluster.py'
      adding 'networkx/algorithms/bipartite/tests/test_edgelist.py'
      adding 'networkx/algorithms/bipartite/tests/test_generators.py'
      adding 'networkx/algorithms/bipartite/tests/test_matching.py'
      adding 'networkx/algorithms/bipartite/tests/test_matrix.py'
      adding 'networkx/algorithms/bipartite/tests/test_project.py'
      adding 'networkx/algorithms/bipartite/tests/test_redundancy.py'
      adding 'networkx/algorithms/bipartite/tests/test_spectral_bipartivity.py'
      adding 'networkx/algorithms/centrality/__init__.py'
      adding 'networkx/algorithms/centrality/betweenness.py'
      adding 'networkx/algorithms/centrality/betweenness_subset.py'
      adding 'networkx/algorithms/centrality/closeness.py'
      adding 'networkx/algorithms/centrality/communicability_alg.py'
      adding 'networkx/algorithms/centrality/current_flow_betweenness.py'
      adding 'networkx/algorithms/centrality/current_flow_betweenness_subset.py'
      adding 'networkx/algorithms/centrality/current_flow_closeness.py'
      adding 'networkx/algorithms/centrality/degree_alg.py'
      adding 'networkx/algorithms/centrality/dispersion.py'
      adding 'networkx/algorithms/centrality/eigenvector.py'
      adding 'networkx/algorithms/centrality/flow_matrix.py'
      adding 'networkx/algorithms/centrality/harmonic.py'
      adding 'networkx/algorithms/centrality/katz.py'
      adding 'networkx/algorithms/centrality/load.py'
      adding 'networkx/algorithms/centrality/tests/test_betweenness_centrality.py'
      adding 'networkx/algorithms/centrality/tests/test_betweenness_centrality_subset.py'
      adding 'networkx/algorithms/centrality/tests/test_closeness_centrality.py'
      adding 'networkx/algorithms/centrality/tests/test_communicability.py'
      adding 'networkx/algorithms/centrality/tests/test_current_flow_betweenness_centrality.py'
      adding 'networkx/algorithms/centrality/tests/test_current_flow_betweenness_centrality_subset.py'
      adding 'networkx/algorithms/centrality/tests/test_current_flow_closeness.py'
      adding 'networkx/algorithms/centrality/tests/test_degree_centrality.py'
      adding 'networkx/algorithms/centrality/tests/test_dispersion.py'
      adding 'networkx/algorithms/centrality/tests/test_eigenvector_centrality.py'
      adding 'networkx/algorithms/centrality/tests/test_harmonic_centrality.py'
      adding 'networkx/algorithms/centrality/tests/test_katz_centrality.py'
      adding 'networkx/algorithms/centrality/tests/test_load_centrality.py'
      adding 'networkx/algorithms/chordal/__init__.py'
      adding 'networkx/algorithms/chordal/chordal_alg.py'
      adding 'networkx/algorithms/chordal/tests/test_chordal.py'
      adding 'networkx/algorithms/coloring/__init__.py'
      adding 'networkx/algorithms/coloring/greedy_coloring.py'
      adding 'networkx/algorithms/coloring/greedy_coloring_with_interchange.py'
      adding 'networkx/algorithms/coloring/tests/test_coloring.py'
      adding 'networkx/algorithms/community/__init__.py'
      adding 'networkx/algorithms/community/kclique.py'
      adding 'networkx/algorithms/community/tests/test_kclique.py'
      adding 'networkx/algorithms/components/__init__.py'
      adding 'networkx/algorithms/components/attracting.py'
      adding 'networkx/algorithms/components/biconnected.py'
      adding 'networkx/algorithms/components/connected.py'
      adding 'networkx/algorithms/components/semiconnected.py'
      adding 'networkx/algorithms/components/strongly_connected.py'
      adding 'networkx/algorithms/components/weakly_connected.py'
      adding 'networkx/algorithms/components/tests/test_attracting.py'
      adding 'networkx/algorithms/components/tests/test_biconnected.py'
      adding 'networkx/algorithms/components/tests/test_connected.py'
      adding 'networkx/algorithms/components/tests/test_semiconnected.py'
      adding 'networkx/algorithms/components/tests/test_strongly_connected.py'
      adding 'networkx/algorithms/components/tests/test_subgraph_copies.py'
      adding 'networkx/algorithms/components/tests/test_weakly_connected.py'
      adding 'networkx/algorithms/connectivity/__init__.py'
      adding 'networkx/algorithms/connectivity/connectivity.py'
      adding 'networkx/algorithms/connectivity/cuts.py'
      adding 'networkx/algorithms/connectivity/kcomponents.py'
      adding 'networkx/algorithms/connectivity/kcutsets.py'
      adding 'networkx/algorithms/connectivity/stoerwagner.py'
      adding 'networkx/algorithms/connectivity/utils.py'
      adding 'networkx/algorithms/connectivity/tests/test_connectivity.py'
      adding 'networkx/algorithms/connectivity/tests/test_cuts.py'
      adding 'networkx/algorithms/connectivity/tests/test_kcomponents.py'
      adding 'networkx/algorithms/connectivity/tests/test_kcutsets.py'
      adding 'networkx/algorithms/connectivity/tests/test_stoer_wagner.py'
      adding 'networkx/algorithms/flow/__init__.py'
      adding 'networkx/algorithms/flow/capacityscaling.py'
      adding 'networkx/algorithms/flow/edmondskarp.py'
      adding 'networkx/algorithms/flow/maxflow.py'
      adding 'networkx/algorithms/flow/mincost.py'
      adding 'networkx/algorithms/flow/networksimplex.py'
      adding 'networkx/algorithms/flow/preflowpush.py'
      adding 'networkx/algorithms/flow/shortestaugmentingpath.py'
      adding 'networkx/algorithms/flow/utils.py'
      adding 'networkx/algorithms/flow/tests/gl1.gpickle.bz2'
      adding 'networkx/algorithms/flow/tests/gw1.gpickle.bz2'
      adding 'networkx/algorithms/flow/tests/netgen-2.gpickle.bz2'
      adding 'networkx/algorithms/flow/tests/test_maxflow.py'
      adding 'networkx/algorithms/flow/tests/test_maxflow_large_graph.py'
      adding 'networkx/algorithms/flow/tests/test_mincost.py'
      adding 'networkx/algorithms/flow/tests/wlm3.gpickle.bz2'
      adding 'networkx/algorithms/isomorphism/__init__.py'
      adding 'networkx/algorithms/isomorphism/isomorph.py'
      adding 'networkx/algorithms/isomorphism/isomorphvf2.py'
      adding 'networkx/algorithms/isomorphism/matchhelpers.py'
      adding 'networkx/algorithms/isomorphism/vf2userfunc.py'
      adding 'networkx/algorithms/isomorphism/tests/iso_r01_s80.A99'
      adding 'networkx/algorithms/isomorphism/tests/iso_r01_s80.B99'
      adding 'networkx/algorithms/isomorphism/tests/si2_b06_m200.A99'
      adding 'networkx/algorithms/isomorphism/tests/si2_b06_m200.B99'
      adding 'networkx/algorithms/isomorphism/tests/test_isomorphism.py'
      adding 'networkx/algorithms/isomorphism/tests/test_isomorphvf2.py'
      adding 'networkx/algorithms/isomorphism/tests/test_vf2userfunc.py'
      adding 'networkx/algorithms/link_analysis/__init__.py'
      adding 'networkx/algorithms/link_analysis/hits_alg.py'
      adding 'networkx/algorithms/link_analysis/pagerank_alg.py'
      adding 'networkx/algorithms/link_analysis/tests/test_hits.py'
      adding 'networkx/algorithms/link_analysis/tests/test_pagerank.py'
      adding 'networkx/algorithms/operators/__init__.py'
      adding 'networkx/algorithms/operators/all.py'
      adding 'networkx/algorithms/operators/binary.py'
      adding 'networkx/algorithms/operators/product.py'
      adding 'networkx/algorithms/operators/unary.py'
      adding 'networkx/algorithms/operators/tests/test_all.py'
      adding 'networkx/algorithms/operators/tests/test_binary.py'
      adding 'networkx/algorithms/operators/tests/test_product.py'
      adding 'networkx/algorithms/operators/tests/test_unary.py'
      adding 'networkx/algorithms/shortest_paths/__init__.py'
      adding 'networkx/algorithms/shortest_paths/astar.py'
      adding 'networkx/algorithms/shortest_paths/dense.py'
      adding 'networkx/algorithms/shortest_paths/generic.py'
      adding 'networkx/algorithms/shortest_paths/unweighted.py'
      adding 'networkx/algorithms/shortest_paths/weighted.py'
      adding 'networkx/algorithms/shortest_paths/tests/test_astar.py'
      adding 'networkx/algorithms/shortest_paths/tests/test_dense.py'
      adding 'networkx/algorithms/shortest_paths/tests/test_dense_numpy.py'
      adding 'networkx/algorithms/shortest_paths/tests/test_generic.py'
      adding 'networkx/algorithms/shortest_paths/tests/test_unweighted.py'
      adding 'networkx/algorithms/shortest_paths/tests/test_weighted.py'
      adding 'networkx/algorithms/tests/test_block.py'
      adding 'networkx/algorithms/tests/test_boundary.py'
      adding 'networkx/algorithms/tests/test_clique.py'
      adding 'networkx/algorithms/tests/test_cluster.py'
      adding 'networkx/algorithms/tests/test_core.py'
      adding 'networkx/algorithms/tests/test_cycles.py'
      adding 'networkx/algorithms/tests/test_dag.py'
      adding 'networkx/algorithms/tests/test_distance_measures.py'
      adding 'networkx/algorithms/tests/test_distance_regular.py'
      adding 'networkx/algorithms/tests/test_dominance.py'
      adding 'networkx/algorithms/tests/test_dominating.py'
      adding 'networkx/algorithms/tests/test_euler.py'
      adding 'networkx/algorithms/tests/test_graphical.py'
      adding 'networkx/algorithms/tests/test_hierarchy.py'
      adding 'networkx/algorithms/tests/test_hybrid.py'
      adding 'networkx/algorithms/tests/test_link_prediction.py'
      adding 'networkx/algorithms/tests/test_matching.py'
      adding 'networkx/algorithms/tests/test_minors.py'
      adding 'networkx/algorithms/tests/test_mis.py'
      adding 'networkx/algorithms/tests/test_mst.py'
      adding 'networkx/algorithms/tests/test_richclub.py'
      adding 'networkx/algorithms/tests/test_simple_paths.py'
      adding 'networkx/algorithms/tests/test_smetric.py'
      adding 'networkx/algorithms/tests/test_swap.py'
      adding 'networkx/algorithms/tests/test_triads.py'
      adding 'networkx/algorithms/tests/test_vitality.py'
      adding 'networkx/algorithms/traversal/__init__.py'
      adding 'networkx/algorithms/traversal/breadth_first_search.py'
      adding 'networkx/algorithms/traversal/depth_first_search.py'
      adding 'networkx/algorithms/traversal/edgedfs.py'
      adding 'networkx/algorithms/traversal/tests/test_bfs.py'
      adding 'networkx/algorithms/traversal/tests/test_dfs.py'
      adding 'networkx/algorithms/traversal/tests/test_edgedfs.py'
      adding 'networkx/algorithms/tree/__init__.py'
      adding 'networkx/algorithms/tree/branchings.py'
      adding 'networkx/algorithms/tree/recognition.py'
      adding 'networkx/algorithms/tree/tests/test_branchings.py'
      adding 'networkx/algorithms/tree/tests/test_recognition.py'
      adding 'networkx/classes/__init__.py'
      adding 'networkx/classes/digraph.py'
      adding 'networkx/classes/function.py'
      adding 'networkx/classes/graph.py'
      adding 'networkx/classes/multidigraph.py'
      adding 'networkx/classes/multigraph.py'
      adding 'networkx/classes/ordered.py'
      adding 'networkx/classes/tests/historical_tests.py'
      adding 'networkx/classes/tests/test_digraph.py'
      adding 'networkx/classes/tests/test_digraph_historical.py'
      adding 'networkx/classes/tests/test_function.py'
      adding 'networkx/classes/tests/test_graph.py'
      adding 'networkx/classes/tests/test_graph_historical.py'
      adding 'networkx/classes/tests/test_multidigraph.py'
      adding 'networkx/classes/tests/test_multigraph.py'
      adding 'networkx/classes/tests/test_ordered.py'
      adding 'networkx/classes/tests/test_special.py'
      adding 'networkx/classes/tests/test_timing.py'
      adding 'networkx/classes/tests/timingclasses.py'
      adding 'networkx/drawing/__init__.py'
      adding 'networkx/drawing/layout.py'
      adding 'networkx/drawing/nx_agraph.py'
      adding 'networkx/drawing/nx_pydot.py'
      adding 'networkx/drawing/nx_pylab.py'
      adding 'networkx/drawing/tests/test_agraph.py'
      adding 'networkx/drawing/tests/test_layout.py'
      adding 'networkx/drawing/tests/test_pydot.py'
      adding 'networkx/drawing/tests/test_pylab.py'
      adding 'networkx/external/__init__.py'
      adding 'networkx/generators/__init__.py'
      adding 'networkx/generators/atlas.py'
      adding 'networkx/generators/classic.py'
      adding 'networkx/generators/community.py'
      adding 'networkx/generators/degree_seq.py'
      adding 'networkx/generators/directed.py'
      adding 'networkx/generators/ego.py'
      adding 'networkx/generators/expanders.py'
      adding 'networkx/generators/geometric.py'
      adding 'networkx/generators/intersection.py'
      adding 'networkx/generators/line.py'
      adding 'networkx/generators/nonisomorphic_trees.py'
      adding 'networkx/generators/random_clustered.py'
      adding 'networkx/generators/random_graphs.py'
      adding 'networkx/generators/small.py'
      adding 'networkx/generators/social.py'
      adding 'networkx/generators/stochastic.py'
      adding 'networkx/generators/threshold.py'
      adding 'networkx/generators/tests/test_atlas.py'
      adding 'networkx/generators/tests/test_classic.py'
      adding 'networkx/generators/tests/test_community.py'
      adding 'networkx/generators/tests/test_degree_seq.py'
      adding 'networkx/generators/tests/test_directed.py'
      adding 'networkx/generators/tests/test_ego.py'
      adding 'networkx/generators/tests/test_expanders.py'
      adding 'networkx/generators/tests/test_geometric.py'
      adding 'networkx/generators/tests/test_intersection.py'
      adding 'networkx/generators/tests/test_line.py'
      adding 'networkx/generators/tests/test_nonisomorphic_trees.py'
      adding 'networkx/generators/tests/test_random_clustered.py'
      adding 'networkx/generators/tests/test_random_graphs.py'
      adding 'networkx/generators/tests/test_small.py'
      adding 'networkx/generators/tests/test_stochastic.py'
      adding 'networkx/generators/tests/test_threshold.py'
      adding 'networkx/linalg/__init__.py'
      adding 'networkx/linalg/algebraicconnectivity.py'
      adding 'networkx/linalg/attrmatrix.py'
      adding 'networkx/linalg/graphmatrix.py'
      adding 'networkx/linalg/laplacianmatrix.py'
      adding 'networkx/linalg/modularitymatrix.py'
      adding 'networkx/linalg/spectrum.py'
      adding 'networkx/linalg/tests/test_algebraic_connectivity.py'
      adding 'networkx/linalg/tests/test_graphmatrix.py'
      adding 'networkx/linalg/tests/test_laplacian.py'
      adding 'networkx/linalg/tests/test_modularity.py'
      adding 'networkx/linalg/tests/test_spectrum.py'
      adding 'networkx/readwrite/__init__.py'
      adding 'networkx/readwrite/adjlist.py'
      adding 'networkx/readwrite/edgelist.py'
      adding 'networkx/readwrite/gexf.py'
      adding 'networkx/readwrite/gml.py'
      adding 'networkx/readwrite/gpickle.py'
      adding 'networkx/readwrite/graph6.py'
      adding 'networkx/readwrite/graphml.py'
      adding 'networkx/readwrite/leda.py'
      adding 'networkx/readwrite/multiline_adjlist.py'
      adding 'networkx/readwrite/nx_shp.py'
      adding 'networkx/readwrite/nx_yaml.py'
      adding 'networkx/readwrite/p2g.py'
      adding 'networkx/readwrite/pajek.py'
      adding 'networkx/readwrite/sparse6.py'
      adding 'networkx/readwrite/json_graph/__init__.py'
      adding 'networkx/readwrite/json_graph/adjacency.py'
      adding 'networkx/readwrite/json_graph/node_link.py'
      adding 'networkx/readwrite/json_graph/tree.py'
      adding 'networkx/readwrite/json_graph/tests/test_adjacency.py'
      adding 'networkx/readwrite/json_graph/tests/test_node_link.py'
      adding 'networkx/readwrite/json_graph/tests/test_tree.py'
      adding 'networkx/readwrite/tests/test_adjlist.py'
      adding 'networkx/readwrite/tests/test_edgelist.py'
      adding 'networkx/readwrite/tests/test_gexf.py'
      adding 'networkx/readwrite/tests/test_gml.py'
      adding 'networkx/readwrite/tests/test_gpickle.py'
      adding 'networkx/readwrite/tests/test_graph6.py'
      adding 'networkx/readwrite/tests/test_graphml.py'
      adding 'networkx/readwrite/tests/test_leda.py'
      adding 'networkx/readwrite/tests/test_p2g.py'
      adding 'networkx/readwrite/tests/test_pajek.py'
      adding 'networkx/readwrite/tests/test_shp.py'
      adding 'networkx/readwrite/tests/test_sparse6.py'
      adding 'networkx/readwrite/tests/test_yaml.py'
      adding 'networkx/testing/__init__.py'
      adding 'networkx/testing/utils.py'
      adding 'networkx/testing/tests/test_utils.py'
      adding 'networkx/tests/__init__.py'
      adding 'networkx/tests/benchmark.py'
      adding 'networkx/tests/test.py'
      adding 'networkx/tests/test_convert.py'
      adding 'networkx/tests/test_convert_numpy.py'
      adding 'networkx/tests/test_convert_pandas.py'
      adding 'networkx/tests/test_convert_scipy.py'
      adding 'networkx/tests/test_exceptions.py'
      adding 'networkx/tests/test_relabel.py'
      adding 'networkx/utils/__init__.py'
      adding 'networkx/utils/contextmanagers.py'
      adding 'networkx/utils/decorators.py'
      adding 'networkx/utils/heaps.py'
      adding 'networkx/utils/misc.py'
      adding 'networkx/utils/random_sequence.py'
      adding 'networkx/utils/rcm.py'
      adding 'networkx/utils/union_find.py'
      adding 'networkx/utils/tests/test_contextmanager.py'
      adding 'networkx/utils/tests/test_decorators.py'
      adding 'networkx/utils/tests/test_heaps.py'
      adding 'networkx/utils/tests/test_misc.py'
      adding 'networkx/utils/tests/test_random_sequence.py'
      adding 'networkx/utils/tests/test_rcm.py'
      adding 'networkx/utils/tests/test_unionfind.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/INSTALL.txt'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/LICENSE.txt'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/3d_drawing/mayavi2_spring.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/advanced/eigenvalues.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/advanced/heavy_metal_umlaut.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/advanced/iterated_dynamical_systems.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/advanced/parallel_betweenness.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms/blockmodel.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms/davis_club.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms/hartford_drug.edgelist'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms/krackhardt_centrality.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/algorithms/rcm.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/basic/properties.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/basic/read_write.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/atlas.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/chess_masters.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/chess_masters_WCC.pgn.bz2'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/circular_tree.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/degree_histogram.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/edge_colormap.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/ego_graph.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/four_grids.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/giant_component.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/house_with_colors.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/knuth_miles.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/knuth_miles.txt.gz'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/labels_and_colors.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/lanl_routes.edgelist'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/lanl_routes.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/node_colormap.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/random_geometric_graph.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/sampson.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/simple_path.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/unix_email.mbox'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/unix_email.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/drawing/weighted_graph.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/atlas.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/atlas2.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/degree_sequence.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/erdos_renyi.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/expected_degree_sequence.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/football.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/karate_club.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/knuth_miles.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/knuth_miles.txt.gz'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/napoleon_russian_campaign.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/roget.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/roget_dat.txt.gz'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/unix_email.mbox'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/unix_email.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/words.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/graph/words_dat.txt.gz'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/multigraph/chess_masters.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/multigraph/chess_masters_WCC.pgn.bz2'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/pygraphviz/pygraphviz_attributes.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/pygraphviz/pygraphviz_draw.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/pygraphviz/pygraphviz_simple.py'
      adding 'networkx-1.10.data/data/share/doc/networkx-1.10/examples/pygraphviz/write_dotfile.py'
      adding 'networkx-1.10.dist-info/LICENSE.txt'
      adding 'networkx-1.10.dist-info/METADATA'
      adding 'networkx-1.10.dist-info/WHEEL'
      adding 'networkx-1.10.dist-info/top_level.txt'
      adding 'networkx-1.10.dist-info/RECORD'
      removing build/bdist.linux-x86_64/wheel
      Building wheel for networkx (setup.py) ... [?25l[?25hdone
      Created wheel for networkx: filename=networkx-1.10-py2.py3-none-any.whl size=1317237 sha256=dbdb2367eaddc2f4bd685e7fce41592676080220dfc91ceae9f71e8668302b7f
      Stored in directory: /tmp/user/.cache/pip/wheels/c8/74/b7/491e824ecb0c5a647ece3adfd8127b41a6cf32a3b7896e9abe
    Successfully built networkx
    Installing collected packages: decorator, networkx
    [31mERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
    qkeras 0.8.0 requires tensorflow-model-optimization>=0.2.1, which is not installed.
    gcsfs 2022.8.2 requires google-cloud-storage, which is not installed.
    qkeras 0.8.0 requires networkx>=2.1, but you have networkx 1.10 which is incompatible.[0m[31m
    [0mSuccessfully installed decorator-5.1.1 networkx-1.10
    Note: you may need to restart the kernel to use updated packages.



```python
import pandas as pd
import ast  # fantastic package (https://docs.python.org/3/library/ast.html)
import networkx as nx
import random
import matplotlib.pyplot as plt

%matplotlib inline
```


```python
df = pd.read_csv('tmdb_5000_credits.csv')
df['cast'] = df.cast.apply(ast.literal_eval)
df.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>movie_id</th>
      <th>title</th>
      <th>cast</th>
      <th>crew</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>19995</td>
      <td>Avatar</td>
      <td>[{'cast_id': 242, 'character': 'Jake Sully', '...</td>
      <td>[{"credit_id": "52fe48009251416c750aca23", "de...</td>
    </tr>
    <tr>
      <th>1</th>
      <td>285</td>
      <td>Pirates of the Caribbean: At World's End</td>
      <td>[{'cast_id': 4, 'character': 'Captain Jack Spa...</td>
      <td>[{"credit_id": "52fe4232c3a36847f800b579", "de...</td>
    </tr>
    <tr>
      <th>2</th>
      <td>206647</td>
      <td>Spectre</td>
      <td>[{'cast_id': 1, 'character': 'James Bond', 'cr...</td>
      <td>[{"credit_id": "54805967c3a36829b5002c41", "de...</td>
    </tr>
    <tr>
      <th>3</th>
      <td>49026</td>
      <td>The Dark Knight Rises</td>
      <td>[{'cast_id': 2, 'character': 'Bruce Wayne / Ba...</td>
      <td>[{"credit_id": "52fe4781c3a36847f81398c3", "de...</td>
    </tr>
    <tr>
      <th>4</th>
      <td>49529</td>
      <td>John Carter</td>
      <td>[{'cast_id': 5, 'character': 'John Carter', 'c...</td>
      <td>[{"credit_id": "52fe479ac3a36847f813eaa3", "de...</td>
    </tr>
  </tbody>
</table>
</div>




```python
df['has_bacon'] = df.cast.apply(lambda c: bool([y for y in c if y['name']=='Kevin Bacon']))
df.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>movie_id</th>
      <th>title</th>
      <th>cast</th>
      <th>crew</th>
      <th>has_bacon</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>19995</td>
      <td>Avatar</td>
      <td>[{'cast_id': 242, 'character': 'Jake Sully', '...</td>
      <td>[{"credit_id": "52fe48009251416c750aca23", "de...</td>
      <td>False</td>
    </tr>
    <tr>
      <th>1</th>
      <td>285</td>
      <td>Pirates of the Caribbean: At World's End</td>
      <td>[{'cast_id': 4, 'character': 'Captain Jack Spa...</td>
      <td>[{"credit_id": "52fe4232c3a36847f800b579", "de...</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>206647</td>
      <td>Spectre</td>
      <td>[{'cast_id': 1, 'character': 'James Bond', 'cr...</td>
      <td>[{"credit_id": "54805967c3a36829b5002c41", "de...</td>
      <td>False</td>
    </tr>
    <tr>
      <th>3</th>
      <td>49026</td>
      <td>The Dark Knight Rises</td>
      <td>[{'cast_id': 2, 'character': 'Bruce Wayne / Ba...</td>
      <td>[{"credit_id": "52fe4781c3a36847f81398c3", "de...</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>49529</td>
      <td>John Carter</td>
      <td>[{'cast_id': 5, 'character': 'John Carter', 'c...</td>
      <td>[{"credit_id": "52fe479ac3a36847f813eaa3", "de...</td>
      <td>False</td>
    </tr>
  </tbody>
</table>
</div>




```python
df[df.has_bacon]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>movie_id</th>
      <th>title</th>
      <th>cast</th>
      <th>crew</th>
      <th>has_bacon</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>101</th>
      <td>49538</td>
      <td>X-Men: First Class</td>
      <td>[{'cast_id': 22, 'character': 'Charles Xavier ...</td>
      <td>[{"credit_id": "538d861cc3a368714300461d", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>198</th>
      <td>49524</td>
      <td>R.I.P.D.</td>
      <td>[{'cast_id': 3, 'character': 'Roy Pulsipher', ...</td>
      <td>[{"credit_id": "570b93599251412c740021f0", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>366</th>
      <td>9383</td>
      <td>Hollow Man</td>
      <td>[{'cast_id': 2, 'character': 'Sebastian Caine ...</td>
      <td>[{"credit_id": "52fe44f0c3a36847f80b2f81", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>635</th>
      <td>568</td>
      <td>Apollo 13</td>
      <td>[{'cast_id': 19, 'character': 'Jim Lovell', 'c...</td>
      <td>[{"credit_id": "52fe4253c3a36847f80158f9", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>877</th>
      <td>261023</td>
      <td>Black Mass</td>
      <td>[{'cast_id': 0, 'character': 'James 'Whitey' B...</td>
      <td>[{"credit_id": "56684b69c3a36836ac0033dd", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>925</th>
      <td>50646</td>
      <td>Crazy, Stupid, Love.</td>
      <td>[{'cast_id': 3, 'character': 'Cal Weaver', 'cr...</td>
      <td>[{"credit_id": "565b6197c3a368507d0034b0", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1073</th>
      <td>8987</td>
      <td>The River Wild</td>
      <td>[{'cast_id': 1, 'character': 'Gail Hartman', '...</td>
      <td>[{"credit_id": "52fe44cfc3a36847f80ab353", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1105</th>
      <td>819</td>
      <td>Sleepers</td>
      <td>[{'cast_id': 19, 'character': 'Father Bobby', ...</td>
      <td>[{"credit_id": "52fe427bc3a36847f8022255", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1181</th>
      <td>820</td>
      <td>JFK</td>
      <td>[{'cast_id': 23, 'character': 'Jim Garrison', ...</td>
      <td>[{"credit_id": "52fe427bc3a36847f8022365", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1478</th>
      <td>881</td>
      <td>A Few Good Men</td>
      <td>[{'cast_id': 10, 'character': 'Lt. Daniel Kaff...</td>
      <td>[{"credit_id": "52fe4286c3a36847f8025d91", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1556</th>
      <td>322</td>
      <td>Mystic River</td>
      <td>[{'cast_id': 4, 'character': 'Jimmy Markum', '...</td>
      <td>[{"credit_id": "52fe4237c3a36847f800d051", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1687</th>
      <td>11499</td>
      <td>Frost/Nixon</td>
      <td>[{'cast_id': 6, 'character': 'David Frost', 'c...</td>
      <td>[{"credit_id": "56430a0dc3a36870e0001396", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1786</th>
      <td>1551</td>
      <td>Flatliners</td>
      <td>[{'cast_id': 1, 'character': 'Nelson', 'credit...</td>
      <td>[{"credit_id": "564888e09251413e7f006ed4", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1862</th>
      <td>14177</td>
      <td>Beauty Shop</td>
      <td>[{'cast_id': 4, 'character': 'Gina Norris', 'c...</td>
      <td>[{"credit_id": "52fe45d59251416c75063f8f", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1941</th>
      <td>9729</td>
      <td>Where the Truth Lies</td>
      <td>[{'cast_id': 1, 'character': 'Lanny', 'credit_...</td>
      <td>[{"credit_id": "52fe4523c3a36847f80be93b", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1965</th>
      <td>1788</td>
      <td>Footloose</td>
      <td>[{'cast_id': 1, 'character': 'Ren McCormack', ...</td>
      <td>[{"credit_id": "52fe4315c3a36847f8039007", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>2145</th>
      <td>617</td>
      <td>Wild Things</td>
      <td>[{'cast_id': 9, 'character': 'Sam Lombardo', '...</td>
      <td>[{"credit_id": "52fe425ec3a36847f8018f4b", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>2218</th>
      <td>11835</td>
      <td>Death Sentence</td>
      <td>[{'cast_id': 16, 'character': 'Nick Hume', 'cr...</td>
      <td>[{"credit_id": "52fe448f9251416c7503910f", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>2842</th>
      <td>11601</td>
      <td>Stir of Echoes</td>
      <td>[{'cast_id': 9, 'character': 'Tom Witzky', 'cr...</td>
      <td>[{"credit_id": "52fe44659251416c750332f1", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>2874</th>
      <td>10944</td>
      <td>In the Cut</td>
      <td>[{'cast_id': 1, 'character': 'Frannie', 'credi...</td>
      <td>[{"credit_id": "5628abae9251414cd8001453", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3030</th>
      <td>9362</td>
      <td>Tremors</td>
      <td>[{'cast_id': 1, 'character': 'Valentine McKee'...</td>
      <td>[{"credit_id": "56999dd39251416e8f0004e6", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3344</th>
      <td>17908</td>
      <td>My Dog Skip</td>
      <td>[{'cast_id': 1, 'character': 'Willie Morris', ...</td>
      <td>[{"credit_id": "52fe47519251416c750951ab", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3488</th>
      <td>20794</td>
      <td>Novocaine</td>
      <td>[{'cast_id': 1, 'character': 'Mike', 'credit_i...</td>
      <td>[{"credit_id": "52fe43fac3a368484e008f7b", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3602</th>
      <td>13776</td>
      <td>Diner</td>
      <td>[{'cast_id': 1, 'character': 'Edward 'Eddie' S...</td>
      <td>[{"credit_id": "52fe459a9251416c7505c1fd", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3883</th>
      <td>8469</td>
      <td>Animal House</td>
      <td>[{'cast_id': 1, 'character': 'John "Bluto" Blu...</td>
      <td>[{"credit_id": "52fe44acc3a36847f80a3975", "de...</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4033</th>
      <td>45132</td>
      <td>Super</td>
      <td>[{'cast_id': 3, 'character': 'Frank Darbo', 'c...</td>
      <td>[{"credit_id": "5677fc029251417845001b2d", "de...</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
G = nx.Graph()
added_actor = []

def add_movie_and_actors_to_graph(row):
    G.add_node(row.title, {'type': 'movie', 'color': 'blue'})
    for actor in row.cast:
        if actor['name'] not in added_actor:
            G.add_node(actor['name'], {'type': 'actor', 'color': 'red' if actor['name']=='Kevin Bacon' else 'green'})
            added_actor.append(actor['name'])
        G.add_edge(row.title, actor['name'])


_ = df.apply(lambda r: add_movie_and_actors_to_graph(r), axis=1)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In [306], line 13
          9             added_actor.append(actor['name'])
         10         G.add_edge(row.title, actor['name'])
    ---> 13 _ = df.apply(lambda r: add_movie_and_actors_to_graph(r), axis=1)


    File /usr/local/cloudstor/python/pre/pandas/core/frame.py:8848, in DataFrame.apply(self, func, axis, raw, result_type, args, **kwargs)
       8837 from pandas.core.apply import frame_apply
       8839 op = frame_apply(
       8840     self,
       8841     func=func,
       (...)
       8846     kwargs=kwargs,
       8847 )
    -> 8848 return op.apply().__finalize__(self, method="apply")


    File /usr/local/cloudstor/python/pre/pandas/core/apply.py:733, in FrameApply.apply(self)
        730 elif self.raw:
        731     return self.apply_raw()
    --> 733 return self.apply_standard()


    File /usr/local/cloudstor/python/pre/pandas/core/apply.py:857, in FrameApply.apply_standard(self)
        856 def apply_standard(self):
    --> 857     results, res_index = self.apply_series_generator()
        859     # wrap results
        860     return self.wrap_results(results, res_index)


    File /usr/local/cloudstor/python/pre/pandas/core/apply.py:873, in FrameApply.apply_series_generator(self)
        870 with option_context("mode.chained_assignment", None):
        871     for i, v in enumerate(series_gen):
        872         # ignore SettingWithCopy here in case the user mutates
    --> 873         results[i] = self.f(v)
        874         if isinstance(results[i], ABCSeries):
        875             # If we have a view on v, we need to make a copy because
        876             #  series_generator will swap out the underlying data
        877             results[i] = results[i].copy(deep=False)


    Cell In [306], line 13, in <lambda>(r)
          9             added_actor.append(actor['name'])
         10         G.add_edge(row.title, actor['name'])
    ---> 13 _ = df.apply(lambda r: add_movie_and_actors_to_graph(r), axis=1)


    Cell In [306], line 5, in add_movie_and_actors_to_graph(row)
          4 def add_movie_and_actors_to_graph(row):
    ----> 5     G.add_node(row.title, {'type': 'movie', 'color': 'blue'})
          6     for actor in row.cast:
          7         if actor['name'] not in added_actor:


    TypeError: add_node() takes 2 positional arguments but 3 were given



```python
random_actors = random.sample(added_actor, 5)
random_actors
```


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    Cell In [307], line 1
    ----> 1 random_actors = random.sample(added_actor, 5)
          2 random_actors


    File /cvmfs/sft.cern.ch/lcg/releases/Python/3.9.12-9a1bc/x86_64-centos7-gcc8-opt/lib/python3.9/random.py:449, in Random.sample(self, population, k, counts)
        447 randbelow = self._randbelow
        448 if not 0 <= k <= n:
    --> 449     raise ValueError("Sample larger than population or is negative")
        450 result = [None] * k
        451 setsize = 21        # size of a small set minus size of an empty list


    ValueError: Sample larger than population or is negative



```python
for a in random_actors:
    path = nx.shortest_path(G,source=a,target='Kevin Bacon')
    print('{0} has a Bacon score of: {1}'.format(a, int(len(path)/2)))
    print(path)
```


    ---------------------------------------------------------------------------

    NodeNotFound                              Traceback (most recent call last)

    Cell In [308], line 2
          1 for a in random_actors:
    ----> 2     path = nx.shortest_path(G,source=a,target='Kevin Bacon')
          3     print('{0} has a Bacon score of: {1}'.format(a, int(len(path)/2)))
          4     print(path)


    File /cvmfs/sft.cern.ch/lcg/views/LCG_102swan/x86_64-centos7-gcc8-opt/lib/python3.9/site-packages/networkx/algorithms/shortest_paths/generic.py:160, in shortest_path(G, source, target, weight, method)
        157 else:
        158     # Find shortest source-target path.
        159     if method == "unweighted":
    --> 160         paths = nx.bidirectional_shortest_path(G, source, target)
        161     elif method == "dijkstra":
        162         paths = nx.dijkstra_path(G, source, target, weight)


    File /cvmfs/sft.cern.ch/lcg/views/LCG_102swan/x86_64-centos7-gcc8-opt/lib/python3.9/site-packages/networkx/algorithms/shortest_paths/unweighted.py:221, in bidirectional_shortest_path(G, source, target)
        219 if source not in G or target not in G:
        220     msg = f"Either source {source} or target {target} is not in G"
    --> 221     raise nx.NodeNotFound(msg)
        223 # call helper to do the real work
        224 results = _bidirectional_pred_succ(G, source, target)


    NodeNotFound: Either source e or target Kevin Bacon is not in G



```python

```
