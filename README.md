# Funding Circle Atom configuration

## Prerequisites

- You have [Atom](https://atom.io/) installed :rocket:
- You have [apm](https://github.com/atom/apm) installed  
  Run *Atom > Install Shell Commands* from the menu option

## Instructions

Note: This will wipe out any existing Atom configurations that you have.

```bash
mv ~/.atom ~/.atom_bak
git clone git@github.com:FundingCircle/dotatom.git ~/.atom
```

Install the Atom packages by running:

```
apm install --packages-file package-list.txt
```

If you add or update an Atom package, update the `package-list.txt` file:

```
apm list --installed --bare > package-list.txt
```
