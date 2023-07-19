# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.792 ops/ms
# Warmup Iteration   2: 3.612 ops/ms
# Warmup Iteration   3: 7.009 ops/ms
Iteration   1: 7.461 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 7.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.793 ±(99.9%) 6.163 ops/ms [Average]
  (min, avg, max) = (7.461, 7.793, 8.137), stdev = 0.338
  CI (99.9%): [1.630, 13.956] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.271 ops/ms
# Warmup Iteration   2: 6.859 ops/ms
# Warmup Iteration   3: 8.054 ops/ms
Iteration   1: 8.269 ops/ms
Iteration   2: 8.518 ops/ms
Iteration   3: 8.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.408 ±(99.9%) 2.319 ops/ms [Average]
  (min, avg, max) = (8.269, 8.408, 8.518), stdev = 0.127
  CI (99.9%): [6.089, 10.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.997 ops/ms
# Warmup Iteration   2: 6.618 ops/ms
# Warmup Iteration   3: 7.576 ops/ms
Iteration   1: 7.929 ops/ms
Iteration   2: 8.141 ops/ms
Iteration   3: 8.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.030 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (7.929, 8.030, 8.141), stdev = 0.107
  CI (99.9%): [6.085, 9.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.786 ops/ms
# Warmup Iteration   2: 5.585 ops/ms
# Warmup Iteration   3: 6.377 ops/ms
Iteration   1: 6.710 ops/ms
Iteration   2: 6.904 ops/ms
Iteration   3: 6.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.816 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (6.710, 6.816, 6.904), stdev = 0.098
  CI (99.9%): [5.021, 8.611] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.958 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.587 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.004 ms/op
Iteration   1: 3.897 ±(99.9%) 0.012 ms/op
Iteration   2: 3.817 ±(99.9%) 0.014 ms/op
Iteration   3: 3.836 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.850 ±(99.9%) 0.766 ms/op [Average]
  (min, avg, max) = (3.817, 3.850, 3.897), stdev = 0.042
  CI (99.9%): [3.084, 4.616] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.666 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.007 ms/op
Iteration   1: 3.908 ±(99.9%) 0.010 ms/op
Iteration   2: 3.940 ±(99.9%) 0.006 ms/op
Iteration   3: 3.684 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.844 ±(99.9%) 2.541 ms/op [Average]
  (min, avg, max) = (3.684, 3.844, 3.940), stdev = 0.139
  CI (99.9%): [1.304, 6.385] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.499 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.774 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.004 ms/op
Iteration   1: 3.957 ±(99.9%) 0.011 ms/op
Iteration   2: 4.019 ±(99.9%) 0.011 ms/op
Iteration   3: 4.098 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.025 ±(99.9%) 1.294 ms/op [Average]
  (min, avg, max) = (3.957, 4.025, 4.098), stdev = 0.071
  CI (99.9%): [2.731, 5.319] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.000 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.143 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.012 ±(99.9%) 0.008 ms/op
Iteration   1: 4.870 ±(99.9%) 0.011 ms/op
Iteration   2: 4.675 ±(99.9%) 0.013 ms/op
Iteration   3: 4.713 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.753 ±(99.9%) 1.885 ms/op [Average]
  (min, avg, max) = (4.675, 4.753, 4.870), stdev = 0.103
  CI (99.9%): [2.868, 6.638] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.039 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 5.134 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.701 ±(99.9%) 0.021 ms/op
Iteration   1: 4.069 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  24.838 ms/op
                 createUser·p0.9999: 27.272 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 4.034 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  10.600 ms/op
                 createUser·p0.9999: 28.654 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 4.056 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.954 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.186 ms/op
                 createUser·p0.999:  28.909 ms/op
                 createUser·p0.9999: 34.020 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236628
  mean =      4.053 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 224724 
    [ 5.000,  7.500) = 10013 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.043 ms/op
     p(99.9000) =     24.916 ms/op
     p(99.9900) =     33.139 ms/op
     p(99.9990) =     34.597 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.204 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.013 ms/op
Iteration   1: 3.913 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.987 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.835 ms/op
                 existUser·p0.999:  21.660 ms/op
                 existUser·p0.9999: 24.383 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 3.899 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.753 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  14.103 ms/op
                 existUser·p0.9999: 25.100 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 3.836 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  26.771 ms/op
                 existUser·p0.9999: 29.458 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247207
  mean =      3.883 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183 
    [ 2.500,  5.000) = 234905 
    [ 5.000,  7.500) = 10158 
    [ 7.500, 10.000) = 1475 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     29.051 ms/op
     p(99.9990) =     30.035 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.291 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.011 ms/op
Iteration   1: 4.005 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.982 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  22.713 ms/op
                 getUser·p0.9999: 31.689 ms/op
                 getUser·p1.00:   33.456 ms/op

Iteration   2: 3.973 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.077 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  16.116 ms/op
                 getUser·p0.9999: 26.935 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 3.923 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  27.042 ms/op
                 getUser·p0.9999: 29.945 ms/op
                 getUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241754
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 231452 
    [ 5.000,  7.500) = 8298 
    [ 7.500, 10.000) = 1245 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     22.585 ms/op
     p(99.9900) =     30.353 ms/op
     p(99.9990) =     32.604 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.669 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.646 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.928 ±(99.9%) 0.021 ms/op
Iteration   1: 4.690 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  22.872 ms/op
                 listUser·p0.9999: 25.008 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 4.752 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  19.882 ms/op
                 listUser·p0.9999: 22.596 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   3: 4.602 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  19.169 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205086
  mean =      4.681 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 176466 
    [ 5.000,  7.500) = 24044 
    [ 7.500, 10.000) = 3581 
    [10.000, 12.500) = 426 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.793 ± 6.163  ops/ms
ClientPb.existUser                       thrpt       3   8.408 ± 2.319  ops/ms
ClientPb.getUser                         thrpt       3   8.030 ± 1.945  ops/ms
ClientPb.listUser                        thrpt       3   6.816 ± 1.795  ops/ms
ClientPb.createUser                       avgt       3   3.850 ± 0.766   ms/op
ClientPb.existUser                        avgt       3   3.844 ± 2.541   ms/op
ClientPb.getUser                          avgt       3   4.025 ± 1.294   ms/op
ClientPb.listUser                         avgt       3   4.753 ± 1.885   ms/op
ClientPb.createUser                     sample  236628   4.053 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.726           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.043           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.916           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.139           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.865           ms/op
ClientPb.existUser                      sample  247207   3.883 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.108           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.973           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.430           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  241754   3.967 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.876           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.585           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.353           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.456           ms/op
ClientPb.listUser                       sample  205086   4.681 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.114           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.349           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.100           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.230           ms/op
