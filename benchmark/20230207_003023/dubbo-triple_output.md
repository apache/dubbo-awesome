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
# Warmup Iteration   1: 1.617 ops/ms
# Warmup Iteration   2: 3.706 ops/ms
# Warmup Iteration   3: 6.945 ops/ms
Iteration   1: 7.485 ops/ms
Iteration   2: 7.981 ops/ms
Iteration   3: 7.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.783 ±(99.9%) 4.801 ops/ms [Average]
  (min, avg, max) = (7.485, 7.783, 7.981), stdev = 0.263
  CI (99.9%): [2.983, 12.584] (assumes normal distribution)


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
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 6.190 ops/ms
# Warmup Iteration   3: 7.999 ops/ms
Iteration   1: 8.424 ops/ms
Iteration   2: 8.311 ops/ms
Iteration   3: 8.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.324 ±(99.9%) 1.725 ops/ms [Average]
  (min, avg, max) = (8.236, 8.324, 8.424), stdev = 0.095
  CI (99.9%): [6.598, 10.049] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 6.504 ops/ms
# Warmup Iteration   3: 7.536 ops/ms
Iteration   1: 7.895 ops/ms
Iteration   2: 8.040 ops/ms
Iteration   3: 8.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.018 ±(99.9%) 2.064 ops/ms [Average]
  (min, avg, max) = (7.895, 8.018, 8.118), stdev = 0.113
  CI (99.9%): [5.954, 10.082] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.107 ops/ms
# Warmup Iteration   2: 5.671 ops/ms
# Warmup Iteration   3: 6.287 ops/ms
Iteration   1: 6.839 ops/ms
Iteration   2: 6.839 ops/ms
Iteration   3: 6.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.754 ±(99.9%) 2.667 ops/ms [Average]
  (min, avg, max) = (6.586, 6.754, 6.839), stdev = 0.146
  CI (99.9%): [4.088, 9.421] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.574 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.335 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.008 ms/op
Iteration   1: 4.037 ±(99.9%) 0.012 ms/op
Iteration   2: 3.907 ±(99.9%) 0.014 ms/op
Iteration   3: 4.118 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.021 ±(99.9%) 1.942 ms/op [Average]
  (min, avg, max) = (3.907, 4.021, 4.118), stdev = 0.106
  CI (99.9%): [2.079, 5.963] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.156 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.011 ms/op
Iteration   1: 3.880 ±(99.9%) 0.011 ms/op
Iteration   2: 3.889 ±(99.9%) 0.009 ms/op
Iteration   3: 3.876 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.882 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (3.876, 3.882, 3.889), stdev = 0.007
  CI (99.9%): [3.762, 4.002] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 14.180 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.928 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.008 ms/op
Iteration   1: 4.088 ±(99.9%) 0.003 ms/op
Iteration   2: 4.051 ±(99.9%) 0.010 ms/op
Iteration   3: 4.127 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.088 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (4.051, 4.088, 4.127), stdev = 0.038
  CI (99.9%): [3.394, 4.783] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.539 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.124 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.855 ±(99.9%) 0.011 ms/op
Iteration   1: 4.914 ±(99.9%) 0.012 ms/op
Iteration   2: 4.958 ±(99.9%) 0.008 ms/op
Iteration   3: 4.701 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.858 ±(99.9%) 2.514 ms/op [Average]
  (min, avg, max) = (4.701, 4.858, 4.958), stdev = 0.138
  CI (99.9%): [2.344, 7.371] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 11.023 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 6.717 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 4.738 ±(99.9%) 0.024 ms/op
Iteration   1: 4.207 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.882 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.743 ms/op
                 createUser·p0.99:   8.215 ms/op
                 createUser·p0.999:  17.138 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 4.118 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   8.700 ms/op
                 createUser·p0.999:  26.475 ms/op
                 createUser·p0.9999: 28.549 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.821 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  14.746 ms/op
                 createUser·p0.9999: 35.976 ms/op
                 createUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235170
  mean =      4.080 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191 
    [ 2.500,  5.000) = 220288 
    [ 5.000,  7.500) = 11522 
    [ 7.500, 10.000) = 2135 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     21.556 ms/op
     p(99.9900) =     32.813 ms/op
     p(99.9990) =     37.059 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.206 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.014 ms/op
Iteration   1: 3.799 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.817 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  23.323 ms/op
                 existUser·p0.9999: 29.023 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   2: 3.903 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.855 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  9.585 ms/op
                 existUser·p0.9999: 24.700 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   3: 3.797 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.001 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  24.565 ms/op
                 existUser·p0.9999: 26.809 ms/op
                 existUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250580
  mean =      3.832 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 257 
    [ 2.500,  5.000) = 242749 
    [ 5.000,  7.500) = 6246 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      1.817 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     22.577 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     29.212 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.978 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.016 ms/op
Iteration   1: 4.167 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   6.332 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  13.713 ms/op
                 getUser·p0.9999: 26.279 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 3.897 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  25.887 ms/op
                 getUser·p0.9999: 32.040 ms/op
                 getUser·p1.00:   32.965 ms/op

Iteration   3: 4.140 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  14.093 ms/op
                 getUser·p0.9999: 29.393 ms/op
                 getUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236127
  mean =      4.064 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 221727 
    [ 5.000,  7.500) = 11241 
    [ 7.500, 10.000) = 2312 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 115 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     17.047 ms/op
     p(99.9900) =     30.991 ms/op
     p(99.9990) =     32.864 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 14.992 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.558 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.940 ±(99.9%) 0.019 ms/op
Iteration   1: 5.050 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  25.952 ms/op
                 listUser·p0.9999: 28.573 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   2: 4.758 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 29.664 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   3: 4.764 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  18.478 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197748
  mean =      4.854 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 151289 
    [ 5.000,  7.500) = 40202 
    [ 7.500, 10.000) = 4653 
    [10.000, 12.500) = 1006 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     21.144 ms/op
     p(99.9900) =     28.483 ms/op
     p(99.9990) =     29.990 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.783 ± 4.801  ops/ms
ClientPb.existUser                       thrpt       3   8.324 ± 1.725  ops/ms
ClientPb.getUser                         thrpt       3   8.018 ± 2.064  ops/ms
ClientPb.listUser                        thrpt       3   6.754 ± 2.667  ops/ms
ClientPb.createUser                       avgt       3   4.021 ± 1.942   ms/op
ClientPb.existUser                        avgt       3   3.882 ± 0.120   ms/op
ClientPb.getUser                          avgt       3   4.088 ± 0.694   ms/op
ClientPb.listUser                         avgt       3   4.858 ± 2.514   ms/op
ClientPb.createUser                     sample  235170   4.080 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.706           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.159           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.556           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  250580   3.832 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.817           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.357           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.577           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.213           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.753           ms/op
ClientPb.getUser                        sample  236127   4.064 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.292           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.963           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.047           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.991           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  197748   4.854 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.439           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.617           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.144           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.483           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.310           ms/op
