# Hello there 👋

```cs
using System;
using System.Collections.Generic;

public class BackendDeveloper
{
    public string Name { get; set; } = "ribs351";
    public DateTime DateOfBirth { get; set; } = new DateTime(1997, 2, 16);
    public string CurrentResidency { get; set; } = "Ho Chi Minh City, Vietnam";
    public string Role { get; set; } = "Junior Backend Developer";
    public List<string> SpokenLanguages { get; set; } = new List<string> { "vi_VN", "en_US" };
    public string[] DevelopmentLanguages { get; set; } = { "C#", "Java", "JavaScript", "HTML", "CSS" };
    public string[] Hobbies { get; set; } = { "Coding", "Jogging", "Hiking", "Video editing", "Making memes", "Playing video games" };

    public void SayHi()
    {
        Console.WriteLine("Thanks for dropping by, have a safe and productive day!");
    }
}

class Program
{
    static void Main()
    {
        var me = new BackendDeveloper();
        me.SayHi();
    }
}
