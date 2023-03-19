# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.850 ops/ms
# Warmup Iteration   2: 3.842 ops/ms
# Warmup Iteration   3: 7.330 ops/ms
Iteration   1: 7.134 ops/ms
Iteration   2: 7.837 ops/ms
Iteration   3: 8.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.702 ±(99.9%) 9.368 ops/ms [Average]
  (min, avg, max) = (7.134, 7.702, 8.134), stdev = 0.513
  CI (99.9%): [≈ 0, 17.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.442 ops/ms
# Warmup Iteration   2: 6.860 ops/ms
# Warmup Iteration   3: 8.315 ops/ms
Iteration   1: 7.821 ops/ms
Iteration   2: 7.996 ops/ms
Iteration   3: 8.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.952 ±(99.9%) 2.110 ops/ms [Average]
  (min, avg, max) = (7.821, 7.952, 8.039), stdev = 0.116
  CI (99.9%): [5.842, 10.062] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.299 ops/ms
# Warmup Iteration   2: 6.461 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 8.233 ops/ms
Iteration   2: 7.662 ops/ms
Iteration   3: 8.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.064 ±(99.9%) 6.370 ops/ms [Average]
  (min, avg, max) = (7.662, 8.064, 8.296), stdev = 0.349
  CI (99.9%): [1.694, 14.434] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.119 ops/ms
# Warmup Iteration   2: 5.608 ops/ms
# Warmup Iteration   3: 6.392 ops/ms
Iteration   1: 6.791 ops/ms
Iteration   2: 6.599 ops/ms
Iteration   3: 7.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.805 ±(99.9%) 3.876 ops/ms [Average]
  (min, avg, max) = (6.599, 6.805, 7.024), stdev = 0.212
  CI (99.9%): [2.929, 10.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.967 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.227 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.557 ±(99.9%) 0.006 ms/op
Iteration   1: 3.924 ±(99.9%) 0.014 ms/op
Iteration   2: 3.895 ±(99.9%) 0.012 ms/op
Iteration   3: 3.891 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.904 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (3.891, 3.904, 3.924), stdev = 0.018
  CI (99.9%): [3.574, 4.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.846 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.007 ms/op
Iteration   1: 3.832 ±(99.9%) 0.006 ms/op
Iteration   2: 3.818 ±(99.9%) 0.005 ms/op
Iteration   3: 3.785 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.812 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (3.785, 3.812, 3.832), stdev = 0.024
  CI (99.9%): [3.369, 4.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.755 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.004 ms/op
Iteration   1: 4.089 ±(99.9%) 0.008 ms/op
Iteration   2: 4.153 ±(99.9%) 0.006 ms/op
Iteration   3: 3.949 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.064 ±(99.9%) 1.906 ms/op [Average]
  (min, avg, max) = (3.949, 4.064, 4.153), stdev = 0.104
  CI (99.9%): [2.157, 5.970] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.315 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.554 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.764 ±(99.9%) 0.009 ms/op
Iteration   1: 4.749 ±(99.9%) 0.015 ms/op
Iteration   2: 4.801 ±(99.9%) 0.014 ms/op
Iteration   3: 4.833 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.794 ±(99.9%) 0.779 ms/op [Average]
  (min, avg, max) = (4.749, 4.794, 4.833), stdev = 0.043
  CI (99.9%): [4.016, 5.573] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.959 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.225 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.515 ±(99.9%) 0.019 ms/op
Iteration   1: 4.069 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   7.766 ms/op
                 createUser·p0.999:  27.001 ms/op
                 createUser·p0.9999: 32.978 ms/op
                 createUser·p1.00:   34.144 ms/op

Iteration   2: 3.994 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.017 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 27.917 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 3.923 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.950 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  28.590 ms/op
                 createUser·p0.9999: 34.462 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240236
  mean =      3.995 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188 
    [ 2.500,  5.000) = 222968 
    [ 5.000,  7.500) = 15178 
    [ 7.500, 10.000) = 1325 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     26.370 ms/op
     p(99.9900) =     33.616 ms/op
     p(99.9990) =     35.048 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.206 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.015 ms/op
Iteration   1: 3.891 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.866 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  11.476 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 3.878 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.862 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  25.690 ms/op
                 existUser·p0.9999: 30.327 ms/op
                 existUser·p1.00:   30.966 ms/op

Iteration   3: 3.955 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.810 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  12.699 ms/op
                 existUser·p0.9999: 34.007 ms/op
                 existUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245676
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 395 
    [ 2.500,  5.000) = 234478 
    [ 5.000,  7.500) = 9051 
    [ 7.500, 10.000) = 1279 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     13.014 ms/op
     p(99.9900) =     32.717 ms/op
     p(99.9990) =     34.775 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.404 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.014 ms/op
Iteration   1: 4.069 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  19.091 ms/op
                 getUser·p0.9999: 23.199 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 3.900 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  22.184 ms/op
                 getUser·p0.9999: 25.035 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 4.055 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  11.978 ms/op
                 getUser·p0.9999: 29.655 ms/op
                 getUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239510
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 225619 
    [ 5.000,  7.500) = 11317 
    [ 7.500, 10.000) = 1840 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     30.153 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.686 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.299 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.016 ±(99.9%) 0.018 ms/op
Iteration   1: 4.758 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  25.133 ms/op
                 listUser·p0.9999: 31.241 ms/op
                 listUser·p1.00:   31.949 ms/op

Iteration   2: 4.720 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   8.535 ms/op
                 listUser·p0.999:  17.767 ms/op
                 listUser·p0.9999: 22.253 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   3: 4.673 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.250 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 19.568 ms/op
                 listUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203491
  mean =      4.717 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 172747 
    [ 5.000,  7.500) = 25970 
    [ 7.500, 10.000) = 3823 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.183 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     19.612 ms/op
     p(99.9900) =     29.280 ms/op
     p(99.9990) =     31.521 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.702 ± 9.368  ops/ms
ClientPb.existUser                       thrpt       3   7.952 ± 2.110  ops/ms
ClientPb.getUser                         thrpt       3   8.064 ± 6.370  ops/ms
ClientPb.listUser                        thrpt       3   6.805 ± 3.876  ops/ms
ClientPb.createUser                       avgt       3   3.904 ± 0.330   ms/op
ClientPb.existUser                        avgt       3   3.812 ± 0.443   ms/op
ClientPb.getUser                          avgt       3   4.064 ± 1.906   ms/op
ClientPb.listUser                         avgt       3   4.794 ± 0.779   ms/op
ClientPb.createUser                     sample  240236   3.995 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.239           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.111           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.370           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.616           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.324           ms/op
ClientPb.existUser                      sample  245676   3.908 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.810           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.882           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.037           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.014           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.717           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  239510   4.006 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.413           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.082           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.179           ms/op
ClientPb.listUser                       sample  203491   4.717 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.183           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.612           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.280           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.949           ms/op
