## Manual Experiment Tracking Table

| Experiment ID | Model Type    | Hyperparameters | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUC Score |
| :------------ | :------------ | :-------------- | :------------------ | :---------------- | :--------------- | :-------- | :-------- |
| EXP-01        | Decision Tree | Default         | Dropna, Label Enc   | All features      | 80/20            | 1.000     | 1.000     |
| EXP-02        | Decision Tree | Max depth = 5   | Dropna, Label Enc   | All features      | 80/20            | 0.990     | 0.999     |
| EXP-03        | Decision Tree | Min split = 10  | Dropna, Label Enc   | All features      | 70/30            | 0.987     | 0.986     |
| EXP-04        | Decision Tree | Entropy         | Dropna, Label Enc   | Bill metrics      | 80/20            | 0.938     | 0.973     |
