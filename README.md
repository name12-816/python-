from codecs import backslashreplace_errors

xk_甜品显卡 = ['GTX1060', 'RTX2060', 'RTX3060', 'RTX4060', 'RTX5060']
xk_中低端显卡 = ['GTX1070', 'GTX1070ti', 'RTX2060S', 'RTX3060ti', '4060ti', '5060ti']
xk_中端显卡 = ['GTX1080', 'RTX2070', 'RTX2070S', 'RTX3070', 'RTX3070', 'RTX3070ti', 'RTX4070', 'RTX5070']
xk_中高端显卡 = ['GTX1080ti', 'RTX2080', 'RTX2080ti', 'RTX3080', 'RTX4080', 'RTX5080']
xk_高端显卡 = ['RTX3090', 'RTX4090', 'RTX5090']


class XK:
    def __init__(self, xk_甜品显卡, xk_中低端显卡, xk_中端显卡, xk_中高端显卡, xk_高端显卡):
        self.xk_甜品显卡 = xk_甜品显卡
        self.xk_中低端显卡 = xk_中低端显卡
        self.xk_中端显卡 = xk_中端显卡
        self.xk_中高端显卡 = xk_中高端显卡
        self.xk_高端显卡 = xk_高端显卡

    def xk(self):
        try:
            while True:
                print('欢迎来到显卡购买系统')
                print('1.甜品显卡\n2.中低端显卡\n3.中端显卡\n4.中高端显卡\n5.高端显卡')
                Q = int(input("请输入您每个月的收入："))
                X = int(input('请输入您想购买的显卡型号：\n1.甜品显卡\n2.中低端显卡\n3.中端显卡\n4.中高端显卡\n5.高端显卡\n请输入序号：'))
                if X == 1:
                    print('甜品显卡')
                    print("1.GTX1060 350元 ，2.RTX2060 900元 ， 3.RTX3060 1800元 ， 4.RTX4060 2200元 ， 5.RTX5060 2500元  , 6.退出")
                    xk低端 = int(input('请输入您想购买的显卡型号：'))
                    if xk低端 == 1:
                        print('您选择的显卡是GTX1060')
                        print('您选择的显卡价格是350元')
                        print(f"您当前的现金{ Q - 350}元")
                        break
                    elif xk低端 == 2:
                        print('您选择的显卡是RTX2060')
                        print('您选择的显卡价格是900元')
                        print(f"您当前的现金{ Q - 900}元")
                        break
                    elif xk低端 == 3:
                        print('您选择的显卡是RTX3060')
                        print('您选择的显卡价格是1800元')
                        print(f"您当前的现金{ Q - 1800}元")
                        break
                    elif xk低端 == 4:
                        print('您选择的显卡是RTX4060')
                        print('您选择的显卡价格是2200元')
                        print(f"您当前的现金{ Q - 2200}元")
                        break
                    elif xk低端 == 5:
                        print('您选择的显卡是RTX5060')
                        print('您选择的显卡价格是2500元')
                        print(f"您当前的现金{Q - 2500}元")
                        break
                    elif xk低端 == 6:
                        print("下次欢迎光临")
                        break
                    else:
                        print('请选择您想购买的显卡')
                elif X == 2:
                    print('中低端显卡')
                    print('1.GTX1070 575元， 2.GTX1070ti 750元， 3.RTX2060S 1200元， 4.RTX3060ti 2200元， 5.RTX4060ti 3000元， 6.RTX5060ti 3500元, 7.退出')
                    xk中低端 = int(input('请选择您想购买的显卡'))
                    if xk中低端 == 1:
                        print('您选择的显卡是1070')
                        print("您选择的显卡价格是575元")
                        print(f"您当前的现金{ Q - 575}")
                        break
                    elif xk中低端 == 2:
                        print('您选择的显卡是1070ti')
                        print('您选择的显卡价格是750元')
                        print(f"您当前的现金{ Q - 750}元")
                        break
                    elif xk中低端 == 3:
                        print('您选择的显卡是2060S')
                        print('您选择的显卡价格是1200元')
                        print(f"您当前的现金{ Q - 1200}元")
                        break
                    elif xk中低端 == 4:
                        print('您选择的显卡是3060ti')
                        print('您选择的显卡价格是2200元')
                        print(f"您当前的现金{Q - 2200}元")
                        break
                    elif xk中低端 == 5:
                        print('您选择的显卡是4060ti')
                        print('您选择的显卡价格是3000元')
                        print(f"您当前的现金{ Q - 3000}元")
                        break
                    elif xk中低端 == 6:
                        print('您选择的显卡是5060ti')
                        print('您选择的显卡价格是3500元')
                        print(f"您当前的现金{ Q - 3500}元")
                        break
                    elif xk中低端 == 7:
                        print("下次欢迎光临")
                        break
                    else:
                        print('请选择您想购买的显卡')
                elif X == 3:
                    print('中端显卡')
                    print('1.GTX1080 900元， 3.RTX2070 1500元， 4.RXT2070S 1800元， 5.RTX3070 2300元， 6.RTX3070ti 2600元， 7.RTX4070 3000元， 8.TRX5070 3500元, 9.退出')
                    xk中端 = int(input('请选择您想购买的显卡'))
                    if xk中端 == 1:
                        print('您选择的显卡是1080')
                        print("您选择的显卡价格是900元")
                        print(f"您当前的现金{Q - 900}元")
                        break
                    elif xk中端 == 2:
                        print('您选择的显卡是1080ti')
                        print('您选择的显卡价格是1050元')
                        print(f"您当前的现金{ Q - 1050}元")
                        break
                    elif xk中端 == 3:
                        print('您选择的显卡是2070')
                        print('您选择的显卡价格是1500元')
                        print(f"您当前的现金{Q - 1500}元")
                        break
                    elif xk中端 == 4:
                        print('您选择的显卡是2070S')
                        print('您选择的显卡价格是1800元')
                        print(f"您当前的现金{Q - 1800}元")
                        break
                    elif xk中端 == 5:
                        print('您选择的显卡是3070')
                        print('您选择的显卡价格是2300元')
                        print(f"您当前的现金{Q - 2300}元")
                        break
                    elif xk中端 == 6:
                        print('您选择的显卡是3070ti')
                        print('您选择的显卡价格是2600元')
                        print(f"您当前的现金{Q - 2600}元")
                        break
                    elif xk中端 == 7:
                        print('您选择的显卡是4070')
                        print('您选择的显卡价格是3000元')
                        print(f"您当前的现金{Q - 3000}元")
                        break
                    elif xk中端 == 8:
                        print('您选择的显卡是5070')
                        print('您选择的显卡价格是3500元')
                        print(f"您当前的现金{Q - 3500}元")
                        break
                    elif xk中端 == 9:
                        print("下次欢迎光临")
                        break
                    else:
                        print('请选择您想购买的显卡')
                elif X == 4:
                    print('中高端显卡')
                    print('1.RTX1080ti 1200元 , 2.RXT2080 1600元 ， 3.RTX2080ti 1800元 ， 4.RTX3080 3700元 ， 5.RXT4080 7800元 ，6.RTX5080 8500元 , 7.退出')
                    xk中高端 = int(input('请选择您想购买的显卡'))
                    if xk中高端 == 1:
                        print('您选择的显卡是1080ti')
                        print("您选择的显卡价格是1200元")
                        print(f"您当前的现金{Q - 1200}元")
                        break
                    elif xk中高端 == 2:
                        print('您选择的显卡是2080')
                        print('您选择的显卡价格是1600元')
                        print(f"您当前的现金{Q - 1600}元")
                        break
                    elif xk中高端 == 3:
                        print('您选择的显卡是2080ti')
                        print('您选择的显卡价格是1800元')
                        print(f"您当前的现金{Q - 1800}元")
                        break
                    elif xk中高端 == 4:
                        print('您选择的显卡是3080显卡')
                        print('您选择的显卡价格是3700元')
                        print(f"您当前的现金{Q - 3700}元")
                        break
                    elif xk中高端 == 5:
                        print('您选择的显卡是4080显卡')
                        print('您选择的显卡价格是7800元')
                        print(f"您当前的现金{Q - 7800}元")
                        break
                    elif xk中高端 == 6:
                        print('您选择的显卡是5080显卡')
                        print('您选择的显卡价格是8500元')
                        print(f"您当前的现金{Q - 8500}元")
                        break
                    elif xk中高端 == 7:
                        print("下次欢迎光临")
                        break
                    else :
                        print('请选择您想购买的显卡')
                elif X == 5:
                    print('高端显卡')
                    print('1.RTX3090 5000元', '2.RTX4090 18000元', '3.RTX5090 25000元  4.退出')
                    xk高端 = int(input('请选择您想购买的显卡'))
                    if xk高端 == 1:
                        print('您选择的显卡是3090显卡')
                        print('您选择的显卡价格是5000元')
                        print(f"您当前的现金,{Q - 5000}元")
                        print("下次欢迎光临")
                        break
                    elif xk高端 == 2:
                        print('您选择的显卡是4090显卡')
                        print('您选择的显卡价格是18000元')
                        print(f"您当前的现金,{Q - 18000}")
                        print("下次欢迎光临")
                        break
                    elif xk高端 == 3:
                        print('您选择的显卡是5090显卡')
                        print('您选择的显卡价格是25000元')
                        print(f"您当前的现金{Q - 25000}")
                        print("下次欢迎光临")
                        break
                    elif xk高端 == 4:
                        print("下次欢迎光临")
                        break
                    else:
                        print('请选择您想购买的显卡')
                else:
                    print('请选择您想购买的显卡！')
        except ValueError:
            print("出错了")
mun = XK(xk_甜品显卡, xk_中低端显卡, xk_中端显卡, xk_中高端显卡, xk_高端显卡)
mun.xk()