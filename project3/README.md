In kern/pmap.c, I modified the mem_init() function to allocate and map the envs array

In env.c, I wrote these functions: 
env_init(), env_setup_vm(), region_alloc(), load_icode(), env_create(), env_run()

I also modified trapentry.S and trapentry.c, trapdispatch() function...
