1. Aliaksandr Batyesheu.
2. Contact: 
     * Email: mirrox@tut.by
     * Telegram: @mirrox52
     * VK: https://vk.com/id95133526
     * Phone: +375298584927
3. My goal is self-development. I'm intreresting in web-programming and I want to study HTML/CSS, JavaScript deep.
4. Delphi 3/5, C# 3/5, C++ 2/5, HTML/CSS 3/5.
5. Thread pool in C#:
   ```C#
   public TaskQueue(int count)                                 
        {
            tasks = new ConcurrentQueue<TaskDelegate>();            
            threads = new List<Thread>();                           

            Thread thread;
            for (int i = 0; i < count; i++)                         
            {
                thread = new Thread(new ThreadStart(Work));
                thread.Name = "Thread " + i.ToString();
                threads.Add(thread);
                threads[i].Start();
            }
   ``` 