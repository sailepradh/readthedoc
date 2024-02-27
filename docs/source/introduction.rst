Introduction
=====

.. _background:

Background
------------

Somatic Gene Panel Pipeline (SPP) is a somatic pipeline which is targetted to different types of tumors such as hematological (Myeloid, Lymphoid), Solid Cancer , PARP Inhibtors gene targets. The pipeline can take either paired (Tumor/Normal) or Tumor only analysis.  Structurally, the pipeline consists of common workflow targetted towards the genes targetted towards different biological questions. Furthermore, one can also run reference building and panel of normal workflow (still in testing phase) to generate additional other essential components in somatic analysis pipelines. One can run the pipeline for example for solid tumor diagnosis as shown below


.. code-block:: console

   $ nextflow run main.nf -entry SPP -c nextflow.hopper_test.config --csv Sample.csv -profile solid,hg38

Creating recipes
----------------

For example:

