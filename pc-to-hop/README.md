# PowerCenter to Apache Hop Converter

This tool converts PowerCenter workflows to Apache Hop pipelines.

## Structure

- **parsers/**: XML and parameter parsing modules
  - `xml_parser.py`: PowerCenter XML workflow parser
  - `parameter_parser.py`: PowerCenter parameter parser
  
- **converters/**: Conversion and optimization modules
  - `sql_optimizer.py`: SQL transformation optimizer
  - `hop_builder.py`: Apache Hop workflow builder
  - `transform_mapper.py`: PowerCenter to Hop transform mapper
  
- **converter.py**: Main conversion orchestration module

## Installation

```bash
pip install -r requirements.txt
```

## Dependencies

- lxml: XML parsing and manipulation
- click: Command-line interface creation
