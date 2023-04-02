money = 5000000
name = None
name = input("请输入你的姓名：")


def yu_e(show_header):  # 查询余额
    if show_header:
        print("查询余额".center(32, '-'))
    print(f"{name},您好，您的余额剩余：{money}元")


def cun():  # 存款
    print("存款".center(32, '-'))
    global money
    money += eval(input("请输入您要存款的金额"))
    yu_e(False)


def qu():  # 取款
    print("取款".center(32, '-'))
    global money
    money -= eval(input("请输入您要存款的金额"))
    yu_e(False)


def main():
    print("{主菜单}".center(32, '-'))
    print(f"{name},您好，欢迎来到黑马银行ATm。请选择操作：")
    print("""查询余额\t[输入1]
存款\t\t[输入2]
取款\t\t[输入3]
退出\t\t[输入4]
    """)
    global choice
    choice = eval(input("请输入您的选择："))


while True:
    main()
    if choice == 1:
        yu_e(False)
        continue

    elif choice == 2:
        cun()
        continue
    elif choice == 3:
        qu()
        continue
    else:
        break
