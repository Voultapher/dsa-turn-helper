# DSA Turn Helper

This tools helps you manage DSA(Das Schwarze Auge) turn interactions.

## Helps with:

- Participants
- Initiative
- Health

## Requirements

Somewhat modern browser

## Usage

### Online version

- Open https://voultapher.github.io/dsa-turn-helper/src/dsa-turn-helper.html

### Offline version

- Open https://voultapher.github.io/dsa-turn-helper/src/dsa-turn-helper.html and download the static html page, for example via save as.
- Load the static html page in your browser.

### Example

A quick example of how this tool can be used to assist you in managing a fight
in DSA. First in the Party managing section, you'll want to create parties
appropriate to the fight. Note you can prepare this ahead of time, as it does
not require any fight specific information. Feel free to store and load this
with the 'Load' and 'Download' buttons.

Then once the parties are assembled click on 'All New' in the turn simulation Area.
Changes you make now to the party section will only affect the turn simulation
once you click 'All New' again.

Before the turn simulation can begin, you have the opportunity to enter
initiative roll values for each participant. Once you have entered all the
values you want, click on 'Start'. If a 'INI roll' input has never been changed,
then a random d6 value is assigned for that participants initial initiative roll.

Now that the simulation is set up properly, you'll notice it already sorted
the participants by their base initiative. You are already in the first action
of the battle. The cursor on the left of the participants name shows you
who's action it is currently. Play out the action and adjust health and
initiative values as they change in action 1. Initiative can be changed by
applying effects or by entering a manual value to add, negative numbers are
subtracted. Then step into the next action, by clicking the button with the '>'
symbol. Again play out the action and update the health and initiative values,
in the fields marked with 'H:' and 'I:'. Repeat until the fight is over.
You can go back any time and see how the values and initiative order changed
over the course of turns and rounds. But the history is immutable.

### Tips

Should multiple participants have the
same initiative, feel free to differentiate them with non integer number,
like 16.1, which is more than just 16. By for example choosing effect 'Manual'
and adding 0.1.

## Contributing

Please respect the [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) when contributing.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available,
see the [tags on this repository](https://github.com/Voultapher/once_self_cell/tags).

## Authors

* **Lukas Bergdoll** - *Initial work* - [Voultapher](https://github.com/Voultapher)

See also the list of [contributors](https://github.com/Voultapher/once_self_cell/contributors)
who participated in this project.

## License

This project is licensed under the Apache License, Version 2.0 -
see the [LICENSE.md](LICENSE.md) file for details.

