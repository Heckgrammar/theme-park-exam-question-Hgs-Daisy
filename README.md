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
