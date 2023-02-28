mondat=input('Adj meg egy mondatot és a mondatvégi jel alapján eldöntöm hogy milyen fajtú! ')
szam=int(len(mondat))

if mondat[-1] =='!':
    print('A mondat felkiáltó, felszólító vagy óhajtó.')
    
elif mondat[-1] =='.':
    print('A mondat kijelentő.')    

elif mondat[-1] =='?':
    print('A mondat kérdő.')

else:
    print('A mondat ismeretlen.')