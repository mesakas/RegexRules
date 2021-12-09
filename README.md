# RegexRules
常用正则表达式规则记录


``` Java

/***
 * 正则表达式的常用规则集合
 */
public class RegexRules {

    // 用户名和密码规则（6-30个字符，允许使用：数字、大小写英文字母，和!@#$%^&*()+=<>?:;'"`~_-符号）
    public static String usernameOrPasswordRegex = "[0-9a-zA-Z!@#$%^&*()+=<>?:;'\"`~_-]{6,30}";

    // 邮箱规则（来源参见: https://stackoverflow.com/questions/201323/how-can-i-validate-an-email-address-using-a-regular-expression）
    public static String emailRegex = "(?:[a-z0-9!#$%&'*+/=?^_`{|}~-]+(?:\\.[a-z0-9!#$%&'*+/=?^_`{|}~-]+)*|\"(?:[\\x01-\\x08\\x0b\\x0c\\x0e-\\x1f\\x21\\x23-\\x5b\\x5d-\\x7f]|\\\\[\\x01-\\x09\\x0b\\x0c\\x0e-\\x7f])*\")@(?:(?:[a-z0-9](?:[a-z0-9-]*[a-z0-9])?\\.)+[a-z0-9](?:[a-z0-9-]*[a-z0-9])?|\\[(?:(?:(2(5[0-5]|[0-4][0-9])|1[0-9][0-9]|[1-9]?[0-9]))\\.){3}(?:(2(5[0-5]|[0-4][0-9])|1[0-9][0-9]|[1-9]?[0-9])|[a-z0-9-]*[a-z0-9]:(?:[\\x01-\\x08\\x0b\\x0c\\x0e-\\x1f\\x21-\\x5a\\x53-\\x7f]|\\\\[\\x01-\\x09\\x0b\\x0c\\x0e-\\x7f])+)\\])";


}


```
