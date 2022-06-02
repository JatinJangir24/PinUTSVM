# PinUTSVM
This is a repository for the Pinball Universum Twin Support Vector Machine.

## PinUTSVM Function file documentation:
    function [Predict_Y, TrainTime] = Pin_UTWSVM(TestData, TrainData, UniversumData, FunPara)

Variables:
- TestData = Test Data Matrix. Each row vector of features is a data point, final entry being the data point label.
- TrainData = Train Data Matrix. Each row vector of features is a data point, final entry being the data point label.
- UniversumData = Universum Data Matrix. Each row vector of features is a data point.
- FunPara = a struct containing hyperparameters of PinUTSVM.
- Predict_Y = A column vector of the predictions for TestData.
- TrainTime = Time in seconds taken for training.
