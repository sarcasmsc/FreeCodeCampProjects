import numpy as np

def calculate(list):
    try:
        list = np.array([[list[0], list[1], list[2]], [list[3], list[4], list[5]], [list[6], list[7], list[8]]])
        a = list[:,0]
        b = list[:,1]
        c = list[:,2]
        a2 = list[0,:]
        b2 = list[1,:]
        c2 = list[2,:]
        abc = [a, b, c]
        abc2 = [a2, b2, c2]
        meanaxis1 = [abc[0].mean(), abc[1].mean(), abc[2].mean()]
        meanaxis2 = [abc2[0].mean(), abc2[1].mean(), abc2[2].mean()]
        meanall = list.mean()
        var1 = [abc[0].var(), abc[1].var(), abc[2].var()]
        var2 = [abc2[0].var(), abc2[1].var(), abc2[2].var()]
        varall = list.var()
        std1 = [abc[0].std(), abc[1].std(), abc[2].std()]
        std2 = [abc2[0].std(), abc2[1].std(), abc2[2].std()]
        stdall = list.std()
        max1 = [abc[0].max(), abc[1].max(), abc[2].max()]
        max2 = [abc2[0].max(), abc2[1].max(), abc2[2].max()]
        maxall = list.max()
        min1 = [abc[0].min(), abc[1].min(), abc[2].min()]
        min2 = [abc2[0].min(), abc2[1].min(), abc2[2].min()]
        minall = list.min()
        sum1 = [abc[0].sum(), abc[1].sum(), abc[2].sum()]
        sum2 = [abc2[0].sum(), abc2[1].sum(), abc2[2].sum()]
        sumall = list.sum()
        calculations = {
  'mean': [meanaxis1, meanaxis2, meanall],
  'variance': [var1, var2, varall],
  'standard deviation': [std1, std2, stdall],
  'max': [max1, max2, maxall],
  'min': [min1, min2, minall],
  'sum': [sum1, sum2, sumall]
}

        return calculations
    except:
        raise ValueError("List must contain nine numbers.")
