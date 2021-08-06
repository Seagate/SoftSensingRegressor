# SoftSensingRegressor
The code in this repo was created to tackle the regression task on the soft sensing data obtained by monitoring wafers.

The input data is a combination of data obtained from sensors and several categorical variables describing different parameters of the manufacturing process. The target variables we regress for are statistics describing various measurements performed to QC the produced wafers. So far experiments only involved using the measurement average column ('meas_avg') as a target variable.

The models featured in the notebooks are a transformer-based model, 2 different architectures based on convolutional layers, and an LSTM-based model. The most relevant versions of the models along with the data processing pipeline are implemented in the Regr_single-MT_single-model_custom-loop_experiment.ipynb

There are notebooks desined to plot input data and model prediction by different categories (Extended_plotting.ipynb) and to plot the prediction results together with the ground truth data for QC purposes (Regr_plot_eval.ipynb)
