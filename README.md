# training
def fun(gl_cm,gl_ae):
    gl_cm='gl_cm.csv'
    gl_ae='gl_ae.csv'
    data1=pd.read_csv('gl_cm.csv')
    data2=pd.read_csv('gl_ae.csv')
    df1=pd.DataFrame(data1)
    df2=pd.DataFrame(data2)
    output=pd.concat([df1,df2])
    return output
    shape=shape.output()
    print(shape)


fun(gl_cm,gl_ae)
for i in output['AECONTRT']:
    if i=='Yes':
        print(output[['Subject', 'CMINDC','AETERM']])
        
