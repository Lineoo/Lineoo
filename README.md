# 你好！ :3
🧡这里是Lineo的个人资料！  
🎈喜欢气球嘛  
🧶但是我不会多少语言，只会C#  
🌈请你吃彩虹哦  
🌏你知道我想说什么~  

我说以下几点
>性别：🙅‍♂️我不说🙅‍♀️  
>年龄：💦欸嘿我也不说  
>喜欢的东西：
>>1.我不知道  
>>2.我也不说  
>>3.欸嘿  
>>4.你  
>>5.awa  
>
>直-接-来-吧-!
#
```cs
public class Person
{
    protected Gender gender { get; }
    public uint age { get; }
    public string name { get; } // Lineo
    public Brain brain { get; }

    public class Brain
    {
        public object WhatImThinking { get; set; }
        protected byte[] memories;
    }
    public enum Gender
    {
        Male,
        Female,
        OH_NO_IDONT_WANNA_TELL_YOU,
        Water
    }

    public void OnBirth()
    {
        Console.WriteLine(brain.WhatImThinking);
    }
}
```
```
[EXCEPTION] NullRenferenceException: Object reference not set to an instance of an object.

System.Console.WriteLine(object obj);
EarthOnline.Person.OnBirth();
EarthOnline.World.TimePass();
EarthOnline.World.MessagesLoop();
Mutiverse.Galaxy.OnStart(long no, int seed);
```
