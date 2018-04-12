        double adjustedEarnings;
        double gasPrice;
        double milesDriven;
        double gasUsed;
        int milesPerGallon;
        double totalGasCost;
        double earnings

long startTime = System.currentTimeMillis();
// ... do something ...
long estimatedTime = System.currentTimeMillis() - startTime;

        totalGasCost = milesPerGallon / milesDriven * gasPrice;
        adjustedEarnings = earnings - totalGasCost;
