# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.988 ops/ms
# Warmup Iteration   2: 4.620 ops/ms
# Warmup Iteration   3: 7.615 ops/ms
Iteration   1: 7.850 ops/ms
Iteration   2: 7.946 ops/ms
Iteration   3: 7.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.874 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (7.827, 7.874, 7.946), stdev = 0.063
  CI (99.9%): [6.720, 9.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.200 ops/ms
# Warmup Iteration   2: 6.946 ops/ms
# Warmup Iteration   3: 8.138 ops/ms
Iteration   1: 8.423 ops/ms
Iteration   2: 8.459 ops/ms
Iteration   3: 8.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.425 ±(99.9%) 0.595 ops/ms [Average]
  (min, avg, max) = (8.393, 8.425, 8.459), stdev = 0.033
  CI (99.9%): [7.829, 9.020] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.118 ops/ms
# Warmup Iteration   2: 6.748 ops/ms
# Warmup Iteration   3: 7.910 ops/ms
Iteration   1: 7.629 ops/ms
Iteration   2: 8.011 ops/ms
Iteration   3: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.965 ±(99.9%) 5.766 ops/ms [Average]
  (min, avg, max) = (7.629, 7.965, 8.256), stdev = 0.316
  CI (99.9%): [2.200, 13.731] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.978 ops/ms
# Warmup Iteration   2: 5.515 ops/ms
# Warmup Iteration   3: 6.535 ops/ms
Iteration   1: 6.515 ops/ms
Iteration   2: 6.549 ops/ms
Iteration   3: 6.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.633 ±(99.9%) 3.210 ops/ms [Average]
  (min, avg, max) = (6.515, 6.633, 6.835), stdev = 0.176
  CI (99.9%): [3.424, 9.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.959 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.033 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.462 ±(99.9%) 0.006 ms/op
Iteration   1: 3.972 ±(99.9%) 0.006 ms/op
Iteration   2: 3.932 ±(99.9%) 0.006 ms/op
Iteration   3: 3.939 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.948 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.932, 3.948, 3.972), stdev = 0.021
  CI (99.9%): [3.565, 4.331] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.255 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.004 ms/op
Iteration   1: 4.019 ±(99.9%) 0.004 ms/op
Iteration   2: 3.842 ±(99.9%) 0.006 ms/op
Iteration   3: 3.811 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.891 ±(99.9%) 2.049 ms/op [Average]
  (min, avg, max) = (3.811, 3.891, 4.019), stdev = 0.112
  CI (99.9%): [1.842, 5.940] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.998 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.011 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.007 ms/op
Iteration   1: 4.000 ±(99.9%) 0.005 ms/op
Iteration   2: 3.917 ±(99.9%) 0.006 ms/op
Iteration   3: 3.929 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.949 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.917, 3.949, 4.000), stdev = 0.045
  CI (99.9%): [3.129, 4.769] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.359 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.403 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.706 ±(99.9%) 0.009 ms/op
Iteration   1: 4.658 ±(99.9%) 0.009 ms/op
Iteration   2: 4.697 ±(99.9%) 0.009 ms/op
Iteration   3: 4.637 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.664 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (4.637, 4.664, 4.697), stdev = 0.030
  CI (99.9%): [4.113, 5.215] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.612 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.179 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.716 ±(99.9%) 0.024 ms/op
Iteration   1: 4.195 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   5.014 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  22.587 ms/op
                 createUser·p0.9999: 25.244 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   2: 4.086 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.903 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  16.368 ms/op
                 createUser·p0.9999: 31.599 ms/op
                 createUser·p1.00:   32.735 ms/op

Iteration   3: 4.285 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   5.071 ms/op
                 createUser·p0.95:   6.218 ms/op
                 createUser·p0.99:   9.814 ms/op
                 createUser·p0.999:  29.524 ms/op
                 createUser·p0.9999: 37.981 ms/op
                 createUser·p1.00:   39.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229106
  mean =      4.187 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 575 
    [ 2.500,  5.000) = 206639 
    [ 5.000,  7.500) = 16661 
    [ 7.500, 10.000) = 3454 
    [10.000, 12.500) = 1043 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     22.774 ms/op
     p(99.9900) =     35.407 ms/op
     p(99.9990) =     39.101 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.992 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.780 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.018 ms/op
Iteration   1: 4.009 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.767 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   8.552 ms/op
                 existUser·p0.999:  14.981 ms/op
                 existUser·p0.9999: 26.575 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 3.968 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   8.075 ms/op
                 existUser·p0.999:  19.169 ms/op
                 existUser·p0.9999: 26.468 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   3: 4.210 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.883 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   6.513 ms/op
                 existUser·p0.99:   10.413 ms/op
                 existUser·p0.999:  29.983 ms/op
                 existUser·p0.9999: 44.275 ms/op
                 existUser·p1.00:   44.958 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 236478
  mean =      4.060 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 217065 
    [ 5.000, 10.000) = 17832 
    [10.000, 15.000) = 1216 
    [15.000, 20.000) = 125 
    [20.000, 25.000) = 74 
    [25.000, 30.000) = 91 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     43.516 ms/op
     p(99.9990) =     44.844 ms/op
     p(99.9999) =     44.958 ms/op
    p(100.0000) =     44.958 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.071 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.759 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.016 ms/op
Iteration   1: 4.076 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   10.280 ms/op
                 getUser·p0.999:  22.923 ms/op
                 getUser·p0.9999: 29.201 ms/op
                 getUser·p1.00:   33.325 ms/op

Iteration   2: 4.192 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  16.092 ms/op
                 getUser·p0.9999: 29.559 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 4.194 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.626 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  14.223 ms/op
                 getUser·p0.9999: 34.596 ms/op
                 getUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231085
  mean =      4.153 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 428 
    [ 2.500,  5.000) = 209580 
    [ 5.000,  7.500) = 15108 
    [ 7.500, 10.000) = 3734 
    [10.000, 12.500) = 1479 
    [12.500, 15.000) = 426 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 108 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     21.788 ms/op
     p(99.9900) =     33.420 ms/op
     p(99.9990) =     35.439 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.304 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 5.577 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.266 ±(99.9%) 0.023 ms/op
Iteration   1: 5.101 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   4.592 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.840 ms/op
                 listUser·p0.99:   11.418 ms/op
                 listUser·p0.999:  25.895 ms/op
                 listUser·p0.9999: 32.661 ms/op
                 listUser·p1.00:   34.996 ms/op

Iteration   2: 5.169 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  24.535 ms/op
                 listUser·p0.9999: 32.744 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   3: 5.177 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.275 ms/op
                 listUser·p0.95:   8.061 ms/op
                 listUser·p0.99:   12.501 ms/op
                 listUser·p0.999:  20.452 ms/op
                 listUser·p0.9999: 22.875 ms/op
                 listUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 186449
  mean =      5.149 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 124305 
    [ 5.000,  7.500) = 50238 
    [ 7.500, 10.000) = 8167 
    [10.000, 12.500) = 2049 
    [12.500, 15.000) = 842 
    [15.000, 17.500) = 336 
    [17.500, 20.000) = 188 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     12.026 ms/op
     p(99.9000) =     23.957 ms/op
     p(99.9900) =     32.279 ms/op
     p(99.9990) =     33.750 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.874 ± 1.155  ops/ms
ClientPb.existUser                       thrpt       3   8.425 ± 0.595  ops/ms
ClientPb.getUser                         thrpt       3   7.965 ± 5.766  ops/ms
ClientPb.listUser                        thrpt       3   6.633 ± 3.210  ops/ms
ClientPb.createUser                       avgt       3   3.948 ± 0.383   ms/op
ClientPb.existUser                        avgt       3   3.891 ± 2.049   ms/op
ClientPb.getUser                          avgt       3   3.949 ± 0.820   ms/op
ClientPb.listUser                         avgt       3   4.664 ± 0.551   ms/op
ClientPb.createUser                     sample  229106   4.187 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.630           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.964           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.421           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.774           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.407           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.649           ms/op
ClientPb.existUser                      sample  236478   4.060 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.354           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.841           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.995           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.644           ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.516           ms/op
ClientPb.existUser:existUser·p1.00      sample          44.958           ms/op
ClientPb.getUser                        sample  231085   4.153 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.788           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.420           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.914           ms/op
ClientPb.listUser                       sample  186449   5.149 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.427           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.332           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.971           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.026           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.957           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.279           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.996           ms/op
