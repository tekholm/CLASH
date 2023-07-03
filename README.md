# CLASH
CLASH - Climate-responsive Land Allocation model with carbon Storage and Harvests

CLASH is a biophysical land-use model that describes the allocation of land to different uses, forest growth, terrestrial carbon stocks, and the production of agricultural and forestry goods globally. CLASH is designed to be embedded into integrated assessment models (IAMs), but it can be also run as a stand-alone model with a wrapper file. The model has been written in GAMS. It can be run either as a nonlinear or linear programming problem and under intertemporal optimization.

How to use:
- IAM-integration: include CLASH_Core.gms in your IAM. The IAM needs to provide the set _time_ (alias _t_), subsets _tfirst_ and _tlast_, the objective function and the model and solve statements.
- Stand-alone: use CLASH_Wrapper.gms as the main file

# To get more information
Please refer to the paper describing the model: 

# How to cite
When using the model or parts of it, please cite the paper describing the model: 

# Licence
CLASH is published with MIT License.

# Contributors
Tommi Ekholm, Nadine Freistetter, Aapo Rautiainen, Laura Thölix
