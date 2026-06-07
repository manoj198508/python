# Python Learning Repository

This repository is a collection of Python learning materials focused on core language concepts and concurrency topics. It combines notebooks, slide decks, notes, and small executable scripts for hands-on practice.

## Repository Contents

### Core Python Notebooks
- `01_OOP.ipynb` - object-oriented programming concepts
- `01_OOP_Solutions.ipynb` - solutions for OOP exercises
- `02_Scope_Namespaces.ipynb` - scope and namespace concepts
- `02_Scope_Namespaces_Solutions.ipynb` - solutions for scope and namespace exercises
- `03_Practical_Python.ipynb` - practical Python examples
- `03_Practical_Python_Solutions.ipynb` - solutions for practical Python exercises
- `04_File_Handling.ipynb` - file handling concepts
- `04_File_Handling_Solutions.ipynb` - solutions for file handling exercises
- `Threading.ipynb` - notebook covering threading concepts

### Presentations and Notes
- `01_OOP.pptx`
- `02_Scope_Namespaces.pptx`
- `03_Practical_Python.pptx`
- `04_File_Handling.pptx`
- `Threading_in_Python.pptx`
- `Threading_in_Python_Lecture_Notes-2.docx`

### Concurrency Demo Scripts
- `multiprocess.py` - basic multiprocessing with separate processes
- `multiprocess1.py` - process memory isolation example
- `multiprocess_array.py` - shared array example
- `multiprocess_value.py` - shared value and array example
- `multiprocess_queue.py` - inter-process communication with queues
- `multiprocess_lock.py` - synchronization using locks
- `multiprocess_pool.py` - worker pool example
- `Threadding/thread.py` - threading and GIL notes with runnable examples (`Threadding` is the current folder name in the repository)

## Structure

The repository is organized mainly by topic:
- numbered notebook files for learning modules
- matching solution notebooks for practice
- slide decks and notes for presentation material
- standalone scripts for threading and multiprocessing demonstrations

## Technologies Used

- Python
- Jupyter Notebook
- Python standard library modules such as `threading`, `multiprocessing`, and `time`

## How to Use

1. Open the notebooks in Jupyter Notebook or VS Code.
2. Review the corresponding presentation files for theory.
3. Run the standalone Python scripts to see multiprocessing and threading behavior in action.

Example:

```bash
python multiprocess.py
python Threadding/thread.py
```

## Notes

- This repository does not currently include packaging or dependency-management files such as `pyproject.toml`, `setup.py`, or `requirements.txt`.
- The content is primarily educational and organized for learning rather than as a reusable Python package.