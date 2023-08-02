# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.072 ops/ms
# Warmup Iteration   2: 2.309 ops/ms
# Warmup Iteration   3: 4.868 ops/ms
Iteration   1: 5.536 ops/ms
Iteration   2: 5.478 ops/ms
Iteration   3: 5.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.615 ±(99.9%) 3.475 ops/ms [Average]
  (min, avg, max) = (5.478, 5.615, 5.833), stdev = 0.190
  CI (99.9%): [2.140, 9.091] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.485 ops/ms
# Warmup Iteration   2: 3.984 ops/ms
# Warmup Iteration   3: 5.746 ops/ms
Iteration   1: 6.146 ops/ms
Iteration   2: 5.876 ops/ms
Iteration   3: 5.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.934 ±(99.9%) 3.466 ops/ms [Average]
  (min, avg, max) = (5.780, 5.934, 6.146), stdev = 0.190
  CI (99.9%): [2.468, 9.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.474 ops/ms
# Warmup Iteration   2: 4.004 ops/ms
# Warmup Iteration   3: 5.483 ops/ms
Iteration   1: 5.413 ops/ms
Iteration   2: 5.544 ops/ms
Iteration   3: 5.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.446 ±(99.9%) 1.575 ops/ms [Average]
  (min, avg, max) = (5.381, 5.446, 5.544), stdev = 0.086
  CI (99.9%): [3.872, 7.021] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.553 ops/ms
# Warmup Iteration   2: 3.971 ops/ms
# Warmup Iteration   3: 4.748 ops/ms
Iteration   1: 4.752 ops/ms
Iteration   2: 4.983 ops/ms
Iteration   3: 4.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.887 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (4.752, 4.887, 4.983), stdev = 0.120
  CI (99.9%): [2.688, 7.085] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.596 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.549 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.919 ±(99.9%) 0.008 ms/op
Iteration   1: 5.707 ±(99.9%) 0.008 ms/op
Iteration   2: 5.556 ±(99.9%) 0.012 ms/op
Iteration   3: 5.827 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.697 ±(99.9%) 2.472 ms/op [Average]
  (min, avg, max) = (5.556, 5.697, 5.827), stdev = 0.135
  CI (99.9%): [3.225, 8.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.138 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.512 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.716 ±(99.9%) 0.010 ms/op
Iteration   1: 5.275 ±(99.9%) 0.017 ms/op
Iteration   2: 5.319 ±(99.9%) 0.015 ms/op
Iteration   3: 5.578 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.391 ±(99.9%) 2.993 ms/op [Average]
  (min, avg, max) = (5.275, 5.391, 5.578), stdev = 0.164
  CI (99.9%): [2.398, 8.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.929 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.698 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.972 ±(99.9%) 0.009 ms/op
Iteration   1: 5.905 ±(99.9%) 0.012 ms/op
Iteration   2: 5.958 ±(99.9%) 0.014 ms/op
Iteration   3: 5.575 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.813 ±(99.9%) 3.791 ms/op [Average]
  (min, avg, max) = (5.575, 5.813, 5.958), stdev = 0.208
  CI (99.9%): [2.022, 9.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.490 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 7.711 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.560 ±(99.9%) 0.014 ms/op
Iteration   1: 6.472 ±(99.9%) 0.020 ms/op
Iteration   2: 6.465 ±(99.9%) 0.016 ms/op
Iteration   3: 6.093 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.343 ±(99.9%) 3.960 ms/op [Average]
  (min, avg, max) = (6.093, 6.343, 6.472), stdev = 0.217
  CI (99.9%): [2.383, 10.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.500 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 7.033 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.315 ±(99.9%) 0.032 ms/op
Iteration   1: 5.711 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   7.610 ms/op
                 createUser·p0.95:   8.733 ms/op
                 createUser·p0.99:   12.304 ms/op
                 createUser·p0.999:  24.840 ms/op
                 createUser·p0.9999: 29.229 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   2: 5.628 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   7.119 ms/op
                 createUser·p0.95:   8.046 ms/op
                 createUser·p0.99:   11.141 ms/op
                 createUser·p0.999:  16.272 ms/op
                 createUser·p0.9999: 31.687 ms/op
                 createUser·p1.00:   32.604 ms/op

Iteration   3: 5.677 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.225 ms/op
                 createUser·p0.95:   8.290 ms/op
                 createUser·p0.99:   11.645 ms/op
                 createUser·p0.999:  30.070 ms/op
                 createUser·p0.9999: 32.178 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169131
  mean =      5.672 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 57753 
    [ 5.000,  7.500) = 96494 
    [ 7.500, 10.000) = 11152 
    [10.000, 12.500) = 2495 
    [12.500, 15.000) = 727 
    [15.000, 17.500) = 256 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     24.703 ms/op
     p(99.9900) =     31.755 ms/op
     p(99.9990) =     33.640 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.863 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.228 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.593 ±(99.9%) 0.023 ms/op
Iteration   1: 5.494 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.954 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   7.037 ms/op
                 existUser·p0.95:   8.217 ms/op
                 existUser·p0.99:   10.945 ms/op
                 existUser·p0.999:  22.124 ms/op
                 existUser·p0.9999: 33.337 ms/op
                 existUser·p1.00:   34.341 ms/op

Iteration   2: 5.384 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.138 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.726 ms/op
                 existUser·p0.95:   7.889 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  15.584 ms/op
                 existUser·p0.9999: 28.807 ms/op
                 existUser·p1.00:   29.983 ms/op

Iteration   3: 5.441 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.118 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.898 ms/op
                 existUser·p0.95:   8.126 ms/op
                 existUser·p0.99:   11.223 ms/op
                 existUser·p0.999:  31.303 ms/op
                 existUser·p0.9999: 38.011 ms/op
                 existUser·p1.00:   38.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176346
  mean =      5.439 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 79307 
    [ 5.000,  7.500) = 84862 
    [ 7.500, 10.000) = 9272 
    [10.000, 12.500) = 2063 
    [12.500, 15.000) = 448 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     37.558 ms/op
     p(99.9990) =     38.328 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.614 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 6.646 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.726 ±(99.9%) 0.022 ms/op
Iteration   1: 5.813 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.433 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   7.537 ms/op
                 getUser·p0.95:   8.798 ms/op
                 getUser·p0.99:   12.108 ms/op
                 getUser·p0.999:  23.853 ms/op
                 getUser·p0.9999: 27.410 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   2: 5.784 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.686 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   7.512 ms/op
                 getUser·p0.95:   9.028 ms/op
                 getUser·p0.99:   12.335 ms/op
                 getUser·p0.999:  17.236 ms/op
                 getUser·p0.9999: 34.175 ms/op
                 getUser·p1.00:   34.734 ms/op

Iteration   3: 5.555 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.089 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.971 ms/op
                 getUser·p0.95:   8.102 ms/op
                 getUser·p0.99:   11.660 ms/op
                 getUser·p0.999:  25.622 ms/op
                 getUser·p0.9999: 31.064 ms/op
                 getUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167884
  mean =      5.715 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 56194 
    [ 5.000,  7.500) = 96281 
    [ 7.500, 10.000) = 11087 
    [10.000, 12.500) = 2912 
    [12.500, 15.000) = 960 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.348 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     19.013 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.847 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 8.126 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.547 ±(99.9%) 0.029 ms/op
Iteration   1: 6.790 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   6.455 ms/op
                 listUser·p0.90:   8.348 ms/op
                 listUser·p0.95:   9.699 ms/op
                 listUser·p0.99:   12.648 ms/op
                 listUser·p0.999:  28.731 ms/op
                 listUser·p0.9999: 33.419 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   2: 6.460 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.133 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   11.841 ms/op
                 listUser·p0.999:  27.344 ms/op
                 listUser·p0.9999: 29.920 ms/op
                 listUser·p1.00:   30.081 ms/op

Iteration   3: 6.848 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.092 ms/op
                 listUser·p0.50:   6.373 ms/op
                 listUser·p0.90:   8.985 ms/op
                 listUser·p0.95:   10.306 ms/op
                 listUser·p0.99:   13.566 ms/op
                 listUser·p0.999:  25.438 ms/op
                 listUser·p0.9999: 29.688 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143326
  mean =      6.695 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 7130 
    [ 5.000,  7.500) = 110045 
    [ 7.500, 10.000) = 19725 
    [10.000, 12.500) = 4844 
    [12.500, 15.000) = 954 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.540 ms/op
     p(50.0000) =      6.316 ms/op
     p(90.0000) =      8.471 ms/op
     p(95.0000) =      9.765 ms/op
     p(99.0000) =     12.710 ms/op
     p(99.9000) =     26.957 ms/op
     p(99.9900) =     31.599 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.615 ± 3.475  ops/ms
ClientPb.existUser                       thrpt       3   5.934 ± 3.466  ops/ms
ClientPb.getUser                         thrpt       3   5.446 ± 1.575  ops/ms
ClientPb.listUser                        thrpt       3   4.887 ± 2.198  ops/ms
ClientPb.createUser                       avgt       3   5.697 ± 2.472   ms/op
ClientPb.existUser                        avgt       3   5.391 ± 2.993   ms/op
ClientPb.getUser                          avgt       3   5.813 ± 3.791   ms/op
ClientPb.listUser                         avgt       3   6.343 ± 3.960   ms/op
ClientPb.createUser                     sample  169131   5.672 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.284           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.299           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.389           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.747           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.703           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.755           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.686           ms/op
ClientPb.existUser                      sample  176346   5.439 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.954           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.095           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.889           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.077           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.863           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.547           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.558           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.928           ms/op
ClientPb.getUser                        sample  167884   5.715 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.686           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.333           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.348           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.618           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.075           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.013           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.375           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.734           ms/op
ClientPb.listUser                       sample  143326   6.695 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.316           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.710           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.957           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.599           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.210           ms/op
