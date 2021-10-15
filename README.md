print('\t \t\t \t \t\tTHE BMI CALCULATOR ')
weight = float(input('What is your weight? (Kg) '))
height = float(input('What is your height? (Mtr) '))
bmi = weight/(height*height)

if bmi <= 18.5:
    print('Your BMI is', bmi, 'which means you are underweight \n khaaya peeya karo bhyii thoda sa ')
elif 18.5 < bmi < 25:
    print('Your BMI is', bmi,'which means you are normal \n sab theek hai ;)')
elif 25 < bmi < 30:
    print('your BMI is', bmi,' which means you are overweight \n khaana peena kam karo thoda sa')
elif bmi > 30:
    print('Your BMI is', bmi,'which means you are obese \n dhyaan delo apna')
    print("**Thanks for using our BMI calculator \n health is the priority**")       
