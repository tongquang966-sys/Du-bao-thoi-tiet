import pandas as pd

df_result = pd.DataFrame({
    "Thực tế": y_test,
    "Dự đoán": y_pred
})

df_result.to_csv("ket_qua.csv", index=False)
