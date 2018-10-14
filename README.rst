.. image:: images/lights.png
    :width: 200
=================

This repository illustrates a basic example of reinforcement learning on a traffic light system.
For this, Keras is used on top of Tensorflow in conjunction with SUMO for the traffic simulation.

	
Main Dependencies
============

1. Keras 2.2.2
2. Numpy 1.14.5
3. Tensorflow-gpu 1.10.0
4. Gym 0.10.5
	

Functionalities
===============

A number of scripts are needed to achieve the desired reinforcement learning:

trips.py
--------

For generating new trips on each episode.
sumoEnvQ.py
-----------

For creating the proper environment class with reset() and step() methods.
rlearning.py
------------

For initiating the reinforcement learning through Keras+Tensorflow and eventually testing the results.