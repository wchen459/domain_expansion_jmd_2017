# Beyond the Known: Detecting Novel Feasible Domains over an Unbounded Design Space
Experiment code associated with our JMD paper: "[Beyond the Known: Detecting Novel Feasible Domains over an Unbounded Design Space](https://mechanicaldesign.asmedigitalcollection.asme.org/article.aspx?articleid=2645709)"

![Alt text](/manifold1.png)

To run the Branin example:
```
python exp_branin.py
```

To run the Hosaki example:
```
python exp_hosaki.py
```

To run the two-sphere example:
```
python exp_2spheres.py
```

To run the airfoil example, edit the "source" item in the file "config.ini":
```
source = sf-foil
``` 
and then:
```
python exp_airfoil.py
```

To run the stemless glass example, edit the "source" item in the file "config.ini":
```
source = rw-beer
``` 
and then:
```
python exp_novelty.py
```

To run the bottle example, edit the "source" item in the file "config.ini":
```
source = rw-bottle
``` 
and then:
```
python exp_novelty.py
```

For real-world examples (airfoil, glass, and bottle examples), to synthesize new shapes inside the identified feasible domains:
```
python synthesis.py
```
The plot showing feasible designs will be saved in the folder "synthesized_shapes".


This code is licensed under the MIT license. Feel free to use all or portions for your research or related projects so long as you provide the following citation information:

Chen W, Fuge M. Beyond the Known: Detecting Novel Feasible Domains over an Unbounded Design Space. ASME. J. Mech. Des. to appear.

    @article{chen2017beyond,
      title={Beyond the Known: Detecting Novel Feasible Domains over an Unbounded Design Space},
      author={Chen, Wei and Fuge, Mark},
      journal={Journal of Mechanical Design},
      volume={139},
      number={11},
      pages={111405-111405-10},
      year={2017},  
      publisher={American Society of Mechanical Engineers}
    }

The design manifolds for real-world examples are generated using [the code for our previous paper](https://github.com/IDEALLab/design_embeddings_jmd_2016):

Chen W, Fuge M, Chazan J. Design Manifolds Capture the Intrinsic Complexity and Dimension of Design Spaces. ASME. J. Mech. Des. 2017;139(5):051102-051102-10. doi:10.1115/1.4036134.
