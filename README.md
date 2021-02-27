# Buy-vs.-rent
____________ NOTES ____________

The values for variables within the program do not represent any real scenario or my real financial situation. I changed the values. I believe, though, the values shown represent a realististic scenario for some people.

*** sorry, that within the Notebook everything is in German. I did this for myself at first without documenting at all. Now I'm sharing. Trying to translate soon ***

____________ PURPOSE ____________

This is a Monte Carlo simulation to decide which is cheaper over the long run - buy or rent. 

The thought is, that your property increases in value and you save the rent, but you have the tradeoff of having repair costs and need to pay interest when taking on a loan.

Renting on the other hand let's you invest your money into stocks or whatever investment opportunities you choose. However you will have to pay your rent for the foreseeable future.

____________ INSTALLATION ____________

Since this is a single Jupyter notebook you just have to have Jupyter installed. Libraries you need to have are Numpy, Pandas and Matplotlib. 
On Debian based systems you can run the provided script.

____________ USAGE ____________

If you want to calculate your own situation, you need to fill in the placeholder values for available money and the price of the flat/house you are aiming to purchase or if you dont have one in mind, just fill in your maximum budget. If your estimations for the other parameters differ from mine, feel free to adjust them aswell. 
The nature of a Monte Carlo simulation however reduces the need to change the values a bit. You just might want to change the ranges, e.g. for the interest rate or the return of your investments.

____________ EXAMPLE AND ANALYSIS ____________

![einzel](https://user-images.githubusercontent.com/72806562/109386155-19cd3200-78f9-11eb-86ef-c3928ea80d99.png)

Contrary to popular belief, renting isnt always worse. Of course your financial situation might be more robust against a financial crisis like 2008, as long as you cover your mortgage payments. However, if you invest smart, you might end up more wealthy, if you rent. The analysis revealed an obvious truth though: You'll have the most in the end, the less money you spent and the more money you earn. The lesson seems to be, that it really doesn't matter much if you buy or rent. You should do what you are most comfortable with. 

![monte](https://user-images.githubusercontent.com/72806562/109386303-18503980-78fa-11eb-9a1c-e445d4bc17a3.png)

If you really don't care about investing in the stock market and want the save route, you are probably better off with buying. The Monte Carlo simulation reveals, that buying has a slight probability advantage, and if you buy, you really don't need to be doing anything except keeping your house in good condition, while the stock market could be a lifelong hustle.

![eigenkap](https://user-images.githubusercontent.com/72806562/109386358-80068480-78fa-11eb-92f0-ef5d988b25db.png)

This leaves the question of how much money you want to take on as loan. I thought, it might be better to take on the largest loan you can get and invest your money into stocks, since the return of investment is usually higher than the interest rate, at least with current interest rates. This turns out to be true, but the effect is not as big as I thought. So again, do what you are comfortable with. As usually, there is no clear and definitive recommendation to be made.


