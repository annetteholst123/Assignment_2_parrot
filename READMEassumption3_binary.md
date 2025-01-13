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
