# ä½ å¥½ï¼ :3
ð§¡è¿éæ¯Lineoçä¸ªäººèµæï¼  
ðåæ¬¢æ°çå  
ð§¶ä½æ¯æä¸ä¼å¤å°è¯­è¨ï¼åªä¼C#  
ðè¯·ä½ åå½©è¹å¦  
ðä½ ç¥éææ³è¯´ä»ä¹~  

æè¯´ä»¥ä¸å ç¹
>æ§å«ï¼ðââï¸æä¸è¯´ðââï¸  
>å¹´é¾ï¼ð¦æ¬¸å¿æä¹ä¸è¯´  
>åæ¬¢çä¸è¥¿ï¼
>>1.æä¸ç¥é  
>>2.æä¹ä¸è¯´  
>>3.æ¬¸å¿  
>>4.ä½   
>>5.awa  
>
>ç´-æ¥-æ¥-å§-!
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
