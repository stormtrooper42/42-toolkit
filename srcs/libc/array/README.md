42-toolkit	C Array
==========

## Function

	- init(t_array *v_this, uint (*uf_realloc)(uint size), void (*uf_delete)(void *ptr))
	  /* This function init structure t_array */

	- clear(t_array *v_this)
	  /* This function remove all elements */

	- empty(const t_array *v_this)
	  /* This function return if array is empty */

	- size(const t_array *v_this)
	  /* This function return size of array */

	- capacity(const t_array *v_this)
	  /* This function return capacity of array */

	- push_back(t_array *v_this, void *data)
	  /* This function push data at the end */

	- foreach(t_array *v_this, bool (*funct)(void *ptr))
	  /* This function apply for lot of elements */

	- remove_if(t_array *v_this, bool (*ft_cmp)(void *d1, void *d2), void *data);
	  /* This function destroy element if ft_cmp return true */

	- data(t_array *v_this, TYPEOF)
	  /* This function data pointer */
	  /* WARNING here you pass typeof struct you can (must) see example */

	- destroy(t_array *v_this)
	  /* This function destroy t_array */



## How to use ?

You can see example [here](https://github.com/QuentinPerez/42-toolkit/tree/master/examples/libc/array).

## License

42-toolkit is available under the [GNU General Public License, version 3](LICENSE).