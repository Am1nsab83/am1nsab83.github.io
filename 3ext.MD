امین ثابت اقدم
---

401655019
---

---

main.

```
#include <stdio.h>
int main()
{
    int done = 0, done2 = 0;
    char ch, ch2;
    do
    {
        printf("please enter the option you want:\n1.pay the bill\n2.used internet\n3.buy internet package\n4.buy voice call package\n5.exit\n");
        scanf(" %c", &ch);
        switch (ch)
        {
        case '1':
            do
            {
                printf("how do you wanna pay the bill?:\n1.paypal ( you are in iran though )\n2.*780#\n3.back ( pick me, please )\n");
                scanf(" %c", &ch2);
                switch (ch2)
                {
                case '3':
                    printf("thanks for picking the third option.\n");
                    done2 = 1;
                    break;
                default:
                    printf("sorry, im not programmed till this point, just exit and, yeah... hehe\n");
                    break;
                }
            } while (done2 != 1);
            done2 = 0;
            break;
        case '2':
            do
            {
                printf("so, Im an offline program, but anyways. do you wanna see it in Mb or MB?:\n1.Mb\n2.MB\n3.back( pick me, please )\n");
                scanf(" %c", &ch2);
                switch (ch2)
                {
                case '3':
                    printf("thanks for picking the third option.\n");
                    done2 = 1;
                    break;
                default:
                    printf("sorry, im not programmed till this point, just exit and, yeah... hehe\n");
                    break;
                }
            } while (done2 != 1);
            break;
        case '3':;
            do
            {
                printf("select one:\n1.1MB: 1M Rials\n2.1GB: 1B Rials\n3. back ( pick me, please )\n");
                scanf(" %c", &ch2);
                switch (ch2)
                {
                case '3':
                    printf("thanks for picking the third option.\n");
                    done2 = 1;
                    break;
                default:
                    printf("sorry, im not programmed till this point, just exit and, yeah... hehe\n");
                    break;
                }
            } while (done2 != 1);
            done2 =0;
            break;
        case '4':
            do
            {
                printf("select one ( who uses voice calling in 2023 anyways? )\n1.1H: 9000 Rials\n2.24H: 21000 Rials\n3.back ( pick me, please )\n");
                scanf(" %c", &ch2);
                switch (ch2)
                {
                case '3':
                    printf("thanks for picking the third option.\n");
                    done2 = 1;
                    break;
                default:
                    printf("sorry, im not programmed till this point, just exit and, yeah... hehe\n");
                    break;
                }
            } while (done2 != 1);
            done2=0;
            break;
        case '5':
            done = 1;
            printf("thanks for using this program, please come back :)))).");
            break;
        }
    } while (done != 1);
    return 0;
}
```
out:
```
please enter the option you want:
1.pay the bill
2.used internet
3.buy internet package
4.buy voice call package
5.exit
4
select one ( who uses voice calling in 2023 anyways? )
1.1H: 9000 Rials
2.24H: 21000 Rials
3.back ( pick me, please )
2
sorry, im not programmed till this point, just exit and, yeah... hehe
select one ( who uses voice calling in 2023 anyways? )
1.1H: 9000 Rials
2.24H: 21000 Rials
3.back ( pick me, please )
1
sorry, im not programmed till this point, just exit and, yeah... hehe
select one ( who uses voice calling in 2023 anyways? )
1.1H: 9000 Rials
2.24H: 21000 Rials
3.back ( pick me, please )
3
thanks for picking the third option.
please enter the option you want:
1.pay the bill
2.used internet
3.buy internet package
4.buy voice call package
5.exit
3
select one:
1.1MB: 1M Rials
2.1GB: 1B Rials
3. back ( pick me, please )
1
sorry, im not programmed till this point, just exit and, yeah... hehe
select one:
1.1MB: 1M Rials
2.1GB: 1B Rials
3. back ( pick me, please )
2
sorry, im not programmed till this point, just exit and, yeah... hehe
select one:
1.1MB: 1M Rials
2.1GB: 1B Rials
3. back ( pick me, please )
3
thanks for picking the third option.
please enter the option you want:
1.pay the bill
2.used internet
3.buy internet package
4.buy voice call package
5.exit
5
thanks for using this program, please come back :)))).⏎
```

# [در صورت وجود مشکل یا سوال به این آی دی در تلگرام پیام بدین](https://t.me/am1nsab83)
# [لینک به سایت](https://am1nsab83.github.io/3ext)
# [گیتهاب](https://github.com/Am1nsab83/HW)