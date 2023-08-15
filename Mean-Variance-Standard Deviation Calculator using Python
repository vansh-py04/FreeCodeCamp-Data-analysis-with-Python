import numpy as np


def calculate(list):
  Calculations = {}
  if len(list) != 9:
    raise ValueError("List should have 9 elements")
  else:
    data = np.array(list).reshape(3, 3)
    Calculations['mean'] = [
      np.mean(data, axis=0).tolist(),
      np.mean(data, axis=1),
      np.mean(data.flatten()).tolist()
    ]
    Calculations['variance'] = [
      np.var(data, axis=0).tolist(),
      np.var(data, axis=1),
      np.var(data.flatten()).tolist()
    ]
    Calculations['standard deviation'] = [
      np.std(data, axis=0).tolist(),
      np.std(data, axis=1),
      np.std(data.flatten()).tolist()
    ]
    Calculations['max'] = [
      np.max(data, axis=0).tolist(),
      np.max(data, axis=1),
      np.max(data.flatten()).tolist()
    ]
    Calculations['min'] = [
      np.min(data, axis=0).tolist(),
      np.min(data, axis=1),
      np.min(data.flatten()).tolist()
    ]
    Calculations['sum'] = [
      np.sum(data, axis=0).tolist(),
      np.sum(data, axis=1),
      np.sum(data.flatten()).tolist()
    ]
  return Calculations
