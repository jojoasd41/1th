# 数据集为iacv3，该版本为前三个代理调用模型，最后通过投票的形式进行判断。打标签的方式为[0] in result.
混淆矩阵为[[24,16],[19,41]],Precision=0.7192,recall=0.683,acc=0.65,f1=0.7025

           没有用这个 if '0' in result or '[0]' in result:
                pred = 0
            else:
                pred = 1
