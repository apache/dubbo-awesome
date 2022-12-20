# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.790 ops/ms
# Warmup Iteration   2: 3.889 ops/ms
# Warmup Iteration   3: 7.565 ops/ms
Iteration   1: 7.608 ops/ms
Iteration   2: 7.938 ops/ms
Iteration   3: 7.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.775 ±(99.9%) 3.009 ops/ms [Average]
  (min, avg, max) = (7.608, 7.775, 7.938), stdev = 0.165
  CI (99.9%): [4.767, 10.784] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.394 ops/ms
# Warmup Iteration   2: 6.866 ops/ms
# Warmup Iteration   3: 8.282 ops/ms
Iteration   1: 8.773 ops/ms
Iteration   2: 8.577 ops/ms
Iteration   3: 8.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.563 ±(99.9%) 3.975 ops/ms [Average]
  (min, avg, max) = (8.338, 8.563, 8.773), stdev = 0.218
  CI (99.9%): [4.587, 12.538] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.129 ops/ms
# Warmup Iteration   2: 6.436 ops/ms
# Warmup Iteration   3: 8.172 ops/ms
Iteration   1: 7.870 ops/ms
Iteration   2: 7.952 ops/ms
Iteration   3: 8.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.955 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (7.870, 7.955, 8.043), stdev = 0.087
  CI (99.9%): [6.371, 9.539] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 5.621 ops/ms
# Warmup Iteration   3: 6.927 ops/ms
Iteration   1: 6.799 ops/ms
Iteration   2: 6.919 ops/ms
Iteration   3: 6.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.832 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (6.777, 6.832, 6.919), stdev = 0.076
  CI (99.9%): [5.445, 8.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.265 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.012 ms/op
Iteration   1: 4.072 ±(99.9%) 0.006 ms/op
Iteration   2: 3.903 ±(99.9%) 0.010 ms/op
Iteration   3: 3.776 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.917 ±(99.9%) 2.702 ms/op [Average]
  (min, avg, max) = (3.776, 3.917, 4.072), stdev = 0.148
  CI (99.9%): [1.215, 6.619] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.592 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.004 ms/op
Iteration   1: 3.752 ±(99.9%) 0.007 ms/op
Iteration   2: 3.811 ±(99.9%) 0.013 ms/op
Iteration   3: 3.763 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.775 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (3.752, 3.775, 3.811), stdev = 0.031
  CI (99.9%): [3.209, 4.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.929 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.013 ms/op
Iteration   1: 4.050 ±(99.9%) 0.005 ms/op
Iteration   2: 4.044 ±(99.9%) 0.011 ms/op
Iteration   3: 3.993 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.029 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (3.993, 4.029, 4.050), stdev = 0.031
  CI (99.9%): [3.463, 4.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.226 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.415 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.850 ±(99.9%) 0.005 ms/op
Iteration   1: 4.637 ±(99.9%) 0.008 ms/op
Iteration   2: 4.641 ±(99.9%) 0.016 ms/op
Iteration   3: 4.710 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.663 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (4.637, 4.663, 4.710), stdev = 0.041
  CI (99.9%): [3.912, 5.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.152 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.329 ±(99.9%) 0.018 ms/op
Iteration   1: 3.831 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  9.750 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 3.861 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  26.943 ms/op
                 createUser·p0.9999: 29.884 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   3: 3.909 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.812 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   7.152 ms/op
                 createUser·p0.999:  28.184 ms/op
                 createUser·p0.9999: 30.521 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 248104
  mean =      3.867 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 235 
    [ 2.500,  5.000) = 239842 
    [ 5.000,  7.500) = 6574 
    [ 7.500, 10.000) = 990 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 151 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     25.064 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     32.343 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.732 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.012 ms/op
Iteration   1: 3.755 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.903 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 22.853 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   2: 3.730 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 25.928 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   3: 3.949 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.030 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  18.579 ms/op
                 existUser·p0.9999: 27.329 ms/op
                 existUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251918
  mean =      3.809 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 463 
    [ 2.500,  5.000) = 241973 
    [ 5.000,  7.500) = 8208 
    [ 7.500, 10.000) = 784 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     26.359 ms/op
     p(99.9990) =     27.574 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.941 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.343 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.014 ms/op
Iteration   1: 4.182 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   6.136 ms/op
                 getUser·p0.99:   9.208 ms/op
                 getUser·p0.999:  21.709 ms/op
                 getUser·p0.9999: 28.860 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   2: 3.888 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.997 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.524 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 3.851 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  12.227 ms/op
                 getUser·p0.9999: 32.561 ms/op
                 getUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241866
  mean =      3.968 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 230063 
    [ 5.000,  7.500) = 8625 
    [ 7.500, 10.000) = 2137 
    [10.000, 12.500) = 445 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     20.845 ms/op
     p(99.9900) =     30.960 ms/op
     p(99.9990) =     32.787 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.814 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.728 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.896 ±(99.9%) 0.017 ms/op
Iteration   1: 4.894 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  25.438 ms/op
                 listUser·p0.9999: 27.475 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   2: 4.811 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  21.877 ms/op
                 listUser·p0.9999: 31.076 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   3: 4.819 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 21.203 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198143
  mean =      4.841 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 153292 
    [ 5.000,  7.500) = 38207 
    [ 7.500, 10.000) = 5133 
    [10.000, 12.500) = 896 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     21.852 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     32.753 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.775 ± 3.009  ops/ms
ClientPb.existUser                       thrpt       3   8.563 ± 3.975  ops/ms
ClientPb.getUser                         thrpt       3   7.955 ± 1.584  ops/ms
ClientPb.listUser                        thrpt       3   6.832 ± 1.387  ops/ms
ClientPb.createUser                       avgt       3   3.917 ± 2.702   ms/op
ClientPb.existUser                        avgt       3   3.775 ± 0.567   ms/op
ClientPb.getUser                          avgt       3   4.029 ± 0.566   ms/op
ClientPb.listUser                         avgt       3   4.663 ± 0.750   ms/op
ClientPb.createUser                     sample  248104   3.867 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.358           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.064           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.048           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.834           ms/op
ClientPb.existUser                      sample  251918   3.809 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.606           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.861           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.359           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.623           ms/op
ClientPb.getUser                        sample  241866   3.968 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.231           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.964           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.938           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.845           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.960           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.997           ms/op
ClientPb.listUser                       sample  198143   4.841 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.303           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.439           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.486           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.852           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.656           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.686           ms/op
