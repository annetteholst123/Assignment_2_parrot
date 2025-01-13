```{r}
##Assumption 3 IID Binomial
sleep_data %>% 
  ggplot(aes(x = `Sleep Disorder`, fill = `Sleep Disorder`)) +
  geom_bar() +
  labs(x = "Sleep Disorder",
       y = "Count",
       title = "Distribution of the outcome variable") +
  scale_fill_manual(values = c("Yes" = "pink", "No" = "darkblue")) +
  theme_bw()
```

# When examining the third assumption regarding whether the outcome variable is binary, it is evident that the Sleep Disorder variable has only two possible outcomes. Therefore, the outcome conforms to a binomial distribution.
