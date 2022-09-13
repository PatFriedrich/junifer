
Available pipeline and atlases
==============================


Data Grabbers
^^^^^^^^^^^^^

.. 
    Provide a list of the DataGrabbers that are implemented or planned.
    Access: Valid options are
        - Open
        - Open with registration
        - Restricted
    
    Type/config: this should mention weather the class is built-in in the
    core of junifer or needs to be imported from a specific configuration in
    the `junifer.configs` module.

    State: this should indicate the state of the dataset. Valid options are
    - Planned
    - In Progress
    - Done

    Version added: If the status is "Done", the Junifer version in which the
    dataset was added. Else, a link to the Github issue or pull request
    implementing the dataset. Links to github can be added by using the
    following syntax: :gh:`<issue number>`

.. list-table:: Available data grabbers
   :widths: auto
   :header-rows: 1

   * - Class
     - Description
     - Access
     - Type/Config
     - State
     - Version Added
   * - `DataladHCP1200`
     - `HCP OpenAccess dataset <https://github.com/datalad-datasets/human-connectome-project-openaccess>`_
     - Open with registration
     - Built-in
     - In Progress
     - :gh:`4`
   * - `JuselessDataladUKBVBM`
     - UKB VBM dataset preprocessed with CAT. Available for Juseless only
     - Restricted
     - `junifer.configs.juseless`
     - Done
     - 0.0.1



Markers
^^^^^^^

.. 
    Provide a list of the Markers that are implemented or planned.
    
    State: this should indicate the state of the dataset. Valid options are
    - Planned
    - In Progress
    - Done

    Version added: If the status is "Done", the Junifer version in which the
    dataset was added. Else, a link to the Github issue or pull request
    implementing the dataset. Links to github can be added by using the
    following syntax: :gh:`<issue number>`

.. list-table:: Available data grabbers
   :widths: auto
   :header-rows: 1

   * - Class
     - Description
     - State
     - Version Added
   * - :class:`junifer.markers.ParcelAggregation`
     - Apply parcellation and perform aggregation function
     - Done
     - 0.0.1



Available Atlases and Coordinates
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^



========  =============  =================================================================  =============
Name      Options        Keys                                                               Version added
========  =============  =================================================================  =============
Schaefer  n_rois,        | Schaefer900x7, Schaefer1000x7, Schaefer100x17, Schaefer200x17,   0.0.1
          yeo_networks   | Schaefer500x7, Schaefer600x7, Schaefer700x7, Schaefer800x7,
                         | Schaefer300x17, Schaefer400x17, Schaefer500x17, Schaefer600x17,
                         | Schaefer700x17, Schaefer800x17, Schaefer900x17, Schaefer1000x17
SUIT      space          SUITxMNI, SUITxSUIT                                                0.0.1
TIAN      scale,         | TianxS1x3TxMNI6thgeneration, TianxS1x3TxMNInonlinear2009cAsym,
          space,         | TianxS1x7TxMNI6thgeneration, TianxS2x3TxMNI6thgeneration,
          magneticfield  | TianxS2x3TxMNInonlinear2009cAsym, TianxS2x7TxMNI6thgeneration,
                         | TianxS3x3TxMNI6thgeneration, TianxS3x3TxMNInonlinear2009cAsym,
                         | TianxS3x7TxMNI6thgeneration, TianxS4x3TxMNI6thgeneration,
                         | TianxS4x3TxMNInonlinear2009cAsym, TianxS4x7TxMNI6thgeneration    0.0.1
========  =============  =================================================================  =============


Atlases under consideration
^^^^^^^^^^^^^^^^^^^^^^^^^^^


=================  ==============================================================================
Atlas Names        DOI
=================  ==============================================================================
Desikan-Killiany   http://doi.org/10.1016/j.neuroimage.2006.01.021
Glasser            http://doi.org/10.1038/nature18933
AAL                https://doi.org/10.1016/j.neuroimage.2019.116189
Shen               https://doi.org/10.1016/j.neuroimage.2013.05.081.
Mindboggle 101     http://doi.org/10.3389/fnins.2012.00171/abstract
Destrieux          http://doi.org/10.1016/j.neuroimage.2010.06.010.
Fan                https://doi.org/10.1093/cercor/bhw157
Buckner            | https://doi.org/10.1152/jn.00339.2011
                   | https://doi.org/10.1152/jn.00338.2011
=================  ==============================================================================


Meta-analytical networks (under consideration)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=========================================  ========  ===================================================
Network                                    Acronym   DOI
=========================================  ========  ===================================================
autobiographical memory                    AM        https://doi.org/10.1162/jocn.2008.21029
cognitive attention control                CogAC     https://doi.org/10.1016/j.neubiorev.2014.11.003
extended multiple demand network           eMDN      https://doi.org/10.1016/j.neuroimage.2017.10.020
extended socio-affective default network   eSAD      https://doi.org/10.1007/s00429-013-0698-0
emotional scene and face processing        EmoSF     https://doi.org/10.1016/j.neuroimage.2010.10.011
empathy network                            empathy   https://doi.org/10.1007/s00429-012-0380-y
theory of mind                             ToM       https://doi.org/10.1007/s00429-012-0380-y
emotion regulation                         ER        https://doi.org/10.1093/cercor/bht154
mirror neuron system network               MNS       https://doi.org/10.1016/j.neuroimage.2009.12.112
motor network                              motor     https://doi.org/10.1016/j.neuroimage.2008.04.025
reward network                             Rew       https://doi.org/10.1016/j.neubiorev.2010.12.012
semantic memory                            SM        https://doi.org/10.1016/j.neuroimage.2010.10.039
vigilant attention                         VigAtt    https://doi.org/10.1037/a0030694
working memory                             WM        https://doi.org/10.1016/j.neuroimage.2011.11.050
=========================================  ========  ===================================================


..
  helpful site for creating tables: https://rest-sphinx-memo.readthedocs.io/en/latest/ReST.html#tables
