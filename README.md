            const int ticketPricePerPerson = 15;
            int amountofpeople = 0;
            Console.WriteLine("Enter the number of people in the group:");
            amountofpeople = Convert.ToInt32(Console.ReadLine());
            if (amountofpeople >= 6)
            {
                int totalCharge = (ticketPricePerPerson * amountofpeople) - 5;
                Console.WriteLine($"The total charge for the group is: £{totalCharge}");
            }
            else
            {
                int totalCharge = ticketPricePerPerson * amountofpeople;
                Console.WriteLine($"The total charge for the group is: £{totalCharge}");
<img width="366" height="67" alt="image" src="https://github.com/user-attachments/assets/98e34149-aaf7-4e7c-979c-c4492644a263" />
