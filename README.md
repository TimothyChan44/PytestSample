# PytestSample For Http Api


```
import pytest

class TestXXX(object):
  
  @classmethod
  def setup_class(cls):
    pass
   
  cases_ = [
    {1, },
  ]
  
  @pytest.mark.parametrize('_id,  ,cases_)
  def test_ (self,_id,  ):
    pass
    
  @classmethod
  def teardown_class(cls):
    pass
```


# Snippets For VSCode

```
//
"Print to console": {
		"prefix": "pytest",
		"body": [
			"import pytest",
			"",
			"class Test$1(object):",
			"	'''",
			"	1.$2",
			"	'''",
			"	@classmethod",
			"	def setup_class(cls):",
			"		pass",
			"",
			"	case_$3 = []",
			"",
			"	@pytest.mark.parametrize('$4',case_$3)",
			"	def test_$3(self, $4):",
			"		pass",
			"",
			"	@classmethod",
			"	def teardown_class(cls):",
			"		pass",


		],
		"description": "Log output to console"
	}


```
