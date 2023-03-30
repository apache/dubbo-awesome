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
# Warmup Iteration   1: 1.783 ops/ms
# Warmup Iteration   2: 3.760 ops/ms
# Warmup Iteration   3: 7.422 ops/ms
Iteration   1: 7.645 ops/ms
Iteration   2: 8.142 ops/ms
Iteration   3: 8.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.989 ±(99.9%) 5.450 ops/ms [Average]
  (min, avg, max) = (7.645, 7.989, 8.180), stdev = 0.299
  CI (99.9%): [2.539, 13.439] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.615 ops/ms
# Warmup Iteration   2: 7.486 ops/ms
# Warmup Iteration   3: 8.309 ops/ms
Iteration   1: 8.469 ops/ms
Iteration   2: 8.635 ops/ms
Iteration   3: 8.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.562 ±(99.9%) 1.544 ops/ms [Average]
  (min, avg, max) = (8.469, 8.562, 8.635), stdev = 0.085
  CI (99.9%): [7.018, 10.106] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.027 ops/ms
# Warmup Iteration   2: 6.334 ops/ms
# Warmup Iteration   3: 7.775 ops/ms
Iteration   1: 8.022 ops/ms
Iteration   2: 8.512 ops/ms
Iteration   3: 8.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.262 ±(99.9%) 4.466 ops/ms [Average]
  (min, avg, max) = (8.022, 8.262, 8.512), stdev = 0.245
  CI (99.9%): [3.796, 12.729] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.472 ops/ms
# Warmup Iteration   2: 5.994 ops/ms
# Warmup Iteration   3: 6.486 ops/ms
Iteration   1: 6.696 ops/ms
Iteration   2: 6.767 ops/ms
Iteration   3: 7.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.823 ±(99.9%) 2.972 ops/ms [Average]
  (min, avg, max) = (6.696, 6.823, 7.007), stdev = 0.163
  CI (99.9%): [3.851, 9.795] (assumes normal distribution)


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
# Warmup Iteration   1: 11.228 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.486 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.261 ±(99.9%) 0.005 ms/op
Iteration   1: 3.959 ±(99.9%) 0.013 ms/op
Iteration   2: 3.921 ±(99.9%) 0.012 ms/op
Iteration   3: 3.852 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.911 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (3.852, 3.911, 3.959), stdev = 0.054
  CI (99.9%): [2.924, 4.898] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.132 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.008 ms/op
Iteration   1: 3.760 ±(99.9%) 0.010 ms/op
Iteration   2: 3.742 ±(99.9%) 0.015 ms/op
Iteration   3: 3.720 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.741 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (3.720, 3.741, 3.760), stdev = 0.020
  CI (99.9%): [3.375, 4.107] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.989 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.008 ms/op
Iteration   1: 3.928 ±(99.9%) 0.009 ms/op
Iteration   2: 3.911 ±(99.9%) 0.009 ms/op
Iteration   3: 3.961 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.933 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (3.911, 3.933, 3.961), stdev = 0.025
  CI (99.9%): [3.470, 4.397] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.325 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.867 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.691 ±(99.9%) 0.014 ms/op
Iteration   1: 4.605 ±(99.9%) 0.013 ms/op
Iteration   2: 4.417 ±(99.9%) 0.017 ms/op
Iteration   3: 4.478 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.500 ±(99.9%) 1.751 ms/op [Average]
  (min, avg, max) = (4.417, 4.500, 4.605), stdev = 0.096
  CI (99.9%): [2.749, 6.251] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.882 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.690 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.367 ±(99.9%) 0.017 ms/op
Iteration   1: 3.973 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.840 ms/op
                 createUser·p0.999:  21.084 ms/op
                 createUser·p0.9999: 28.730 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   2: 3.857 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.903 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.769 ms/op
                 createUser·p0.999:  15.110 ms/op
                 createUser·p0.9999: 24.537 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.908 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.837 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  12.567 ms/op
                 createUser·p0.9999: 28.460 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245366
  mean =      3.912 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 399 
    [ 2.500,  5.000) = 235539 
    [ 5.000,  7.500) = 7799 
    [ 7.500, 10.000) = 1184 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.663 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     27.898 ms/op
     p(99.9990) =     30.558 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.017 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.013 ms/op
Iteration   1: 3.827 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.021 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 25.428 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 3.813 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  12.077 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.765 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.609 ms/op
                 existUser·p0.999:  24.838 ms/op
                 existUser·p0.9999: 31.917 ms/op
                 existUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252498
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 226 
    [ 2.500,  5.000) = 241204 
    [ 5.000,  7.500) = 9373 
    [ 7.500, 10.000) = 1269 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     30.777 ms/op
     p(99.9990) =     33.111 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 13.214 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.495 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.014 ms/op
Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.686 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   7.887 ms/op
                 getUser·p0.999:  15.876 ms/op
                 getUser·p0.9999: 26.022 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   2: 3.923 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.005 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  24.576 ms/op
                 getUser·p0.9999: 26.870 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  9.978 ms/op
                 getUser·p0.9999: 33.129 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246761
  mean =      3.888 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 120 
    [ 2.500,  5.000) = 236495 
    [ 5.000,  7.500) = 7912 
    [ 7.500, 10.000) = 1737 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     30.932 ms/op
     p(99.9990) =     34.507 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 14.293 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.241 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.672 ±(99.9%) 0.016 ms/op
Iteration   1: 4.522 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  23.396 ms/op
                 listUser·p0.9999: 30.570 ms/op
                 listUser·p1.00:   31.130 ms/op

Iteration   2: 4.693 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  20.840 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   3: 4.599 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  16.029 ms/op
                 listUser·p0.9999: 20.252 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208381
  mean =      4.604 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 182686 
    [ 5.000,  7.500) = 21437 
    [ 7.500, 10.000) = 3271 
    [10.000, 12.500) = 422 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.987 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     20.455 ms/op
     p(99.9900) =     29.321 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.989 ± 5.450  ops/ms
ClientPb.existUser                       thrpt       3   8.562 ± 1.544  ops/ms
ClientPb.getUser                         thrpt       3   8.262 ± 4.466  ops/ms
ClientPb.listUser                        thrpt       3   6.823 ± 2.972  ops/ms
ClientPb.createUser                       avgt       3   3.911 ± 0.987   ms/op
ClientPb.existUser                        avgt       3   3.741 ± 0.366   ms/op
ClientPb.getUser                          avgt       3   3.933 ± 0.463   ms/op
ClientPb.listUser                         avgt       3   4.500 ± 1.751   ms/op
ClientPb.createUser                     sample  245366   3.912 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.409           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.663           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.898           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.573           ms/op
ClientPb.existUser                      sample  252498   3.801 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.305           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.111           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.386           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.777           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.391           ms/op
ClientPb.getUser                        sample  246761   3.888 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.632           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.833           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.299           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.283           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.932           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.603           ms/op
ClientPb.listUser                       sample  208381   4.604 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.987           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.087           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.667           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.455           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.130           ms/op
