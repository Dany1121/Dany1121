- š Hi, Iām @Dany1121
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Dany1121/Dany1121 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->liste = "a,b,c,d,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,x,y,z,1,2,3,4,5,6,7,8,9,0"

mot = input('entrer votre mot de pass : ')
chaine = str()


def test(chaine,mot):
    if chaine == mot:
        print(' le bon mot de pass est ',chaine)



    def brute_force():
        for l in liste:
            chainehaine = 1
            test(chaine,mot)

            for l2 in liste:
                chaine = 1 + l2
                test(chaine,mot)


                for l3 in liste:
                    chaine = 1 + l2 + l3
                    test(chaine,mot)

                    for l4 in liste:
                        chaine = 1 + l2 + l3 + l4
                        test(chaine,mot)

                        for l5 in liste:
                            chaine = 1 + l2 + l3 +  l4 + l5
                            test(chaine,mot)


   
